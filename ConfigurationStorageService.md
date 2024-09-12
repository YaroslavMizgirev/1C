# Установка сервера хранилища конфигураций 1С для ОС Linux: Astra Linux/Debian
Настройка сервера хранилища конфигураций не сильно отличается от настройки сервиса  RAS. Юнит файл для запуска будет примерно таким же, отличаться только названием и командой запуска сервиса и портом (по-умолчанию 1542).
```BASH
sudo su
mkdir /var/opt/1C
mkdir /var/opt/1C/crserver
chown -R usr1cv8:grp1cv8 /var/opt/1C/crserver

cp /opt/1cv8/x86_64/8.3.24.1586/ras-8.3.24.1586.service /opt/1cv8/x86_64/8.3.24.1586/crs-8.3.24.1586.service
chown usr1cv8:grp1cv8 /opt/1cv8/x86_64/8.3.24.1586/crs-8.3.24.1586.service
vim /opt/1cv8/x86_64/8.3.24.1586/crs-8.3.24.1586.service
```
Исправляем текст в файле `crs-8.3.24.1586.service`:
```Text
[Unit]
Description=1C:Enterprise Configuration Storage Server 8.3 (8.3.24.1586)
After=network.target

[Service]
Type=simple
User=usr1cv8
Group=grp1cv8
# Configuration storage server base
Environment=CRS_DATA=/var/opt/1c/crserver
ExecStart=/bin/sh -c "/opt/1cv8/x86_64/8.3.24.1586/crserver -d ${CRS_DATA}"
KillSignal=SIGINT
Restart=on-failure
RestartSec=5

[Install]
WantedBy=multi-user.target
```
Запускаем созданный сервис `crs-8.3.24.1586.service`:
```BASH
sudo su
ln /opt/1cv8/x86_64/8.3.24.1586/crs-8.3.24.1586.service
systemctl link /opt/1cv8/x86_64/8.3.24.1586/crs-8.3.24.1586.service
systemctl daemon-reload
systemctl enable crs-8.3.24.1586.service # Запустим созданную службу
systemctl start crs-8.3.24.1586.service # Запустим созданную службу
systemctl status crs-8.3.24.1586.service -l --no-pager # Проверим статус новой службы
```
В результате должны увидеть в консоли:
![screen](https://github.com/YaroslavMizgirev/1C/blob/main/images/status%20crs_8_3_24_1586_service.png)

В конфигураторе 1С создаем новое хранилище конфигураций: `tcp://hostname:1542/var/opt/1c/crserver` или `tcp://10.1.12.122:1542/var/opt/1c/crserver` + задаем имя пользователя и пароль для подключения.
