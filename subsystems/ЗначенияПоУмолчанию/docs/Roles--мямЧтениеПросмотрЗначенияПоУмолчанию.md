# Role.мямЧтениеПросмотрЗначенияПоУмолчанию

[← Подсистема](../README.md) · [XML](../src/Roles/мямЧтениеПросмотрЗначенияПоУмолчанию.xml)

UUID образца: `6c7c1476-7060-4be6-949a-d4a369787703`. Формат XML: `2.20`. UUID не менялись; это фрагмент выгрузки, а не полная конфигурация.

## Свойства

| Свойство / путь | Значение | Атрибуты XML |
|---|---|---|
| Name | мямЧтениеПросмотрЗначенияПоУмолчанию |  |
| Synonym/item/lang | ru |  |
| Synonym/item/content | МЯМ: Чтение и просмотр — Значения по умолчанию |  |
| Comment | (пусто) |  |

## Внешние файлы

- [Ext/Rights.xml](../src/Roles/мямЧтениеПросмотрЗначенияПоУмолчанию/Ext/Rights.xml)

## Права

Назначается пользователям/профилям принимающей конфигурации вручную. Права только на собственный каталог; ограничения RLS принимающей конфигурации сохраняются.

| Свойство / путь | Значение | Атрибуты XML |
|---|---|---|
| setForNewObjects | false |  |
| setForAttributesByDefault | true |  |
| independentRightsOfChildObjects | false |  |
| object/name | Catalog.мямЗначенияПоУмолчанию |  |
| object/right[1]/name | Read |  |
| object/right[1]/value | true |  |
| object/right[2]/name | View |  |
| object/right[2]/value | true |  |
| object/right[3]/name | InputByString |  |
| object/right[3]/value | true |  |
