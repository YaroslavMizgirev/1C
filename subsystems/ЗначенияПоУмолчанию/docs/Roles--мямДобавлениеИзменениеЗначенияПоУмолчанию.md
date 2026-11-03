# Role.мямДобавлениеИзменениеЗначенияПоУмолчанию

[← Подсистема](../README.md) · [XML](../src/Roles/мямДобавлениеИзменениеЗначенияПоУмолчанию.xml)

UUID образца: `ce5d0426-f2b9-4c67-8c16-eec44b0aac07`. Формат XML: `2.20`. UUID не менялись; это фрагмент выгрузки, а не полная конфигурация.

## Свойства

| Свойство / путь | Значение | Атрибуты XML |
|---|---|---|
| Name | мямДобавлениеИзменениеЗначенияПоУмолчанию |  |
| Synonym/item/lang | ru |  |
| Synonym/item/content | МЯМ: Добавление и изменение — Значения по умолчанию |  |
| Comment | (пусто) |  |

## Внешние файлы

- [Ext/Rights.xml](../src/Roles/мямДобавлениеИзменениеЗначенияПоУмолчанию/Ext/Rights.xml)

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
| object/right[2]/name | Insert |  |
| object/right[2]/value | true |  |
| object/right[3]/name | Update |  |
| object/right[3]/value | true |  |
| object/right[4]/name | View |  |
| object/right[4]/value | true |  |
| object/right[5]/name | InteractiveInsert |  |
| object/right[5]/value | true |  |
| object/right[6]/name | Edit |  |
| object/right[6]/value | true |  |
| object/right[7]/name | InteractiveSetDeletionMark |  |
| object/right[7]/value | true |  |
| object/right[8]/name | InteractiveClearDeletionMark |  |
| object/right[8]/value | true |  |
| object/right[9]/name | InputByString |  |
| object/right[9]/value | true |  |
