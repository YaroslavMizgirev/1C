# Form.ФормаСписка

[← Подсистема](../README.md) · [XML](../src/Catalogs/мямЗначенияПоУмолчанию/Forms/ФормаСписка.xml)

UUID образца: `cfc4a553-e5f9-4802-9fee-65db57a1ea1e`. Формат XML: `2.20`. UUID не менялись; это фрагмент выгрузки, а не полная конфигурация.

## Свойства

| Свойство / путь | Значение | Атрибуты XML |
|---|---|---|
| Name | ФормаСписка |  |
| Synonym/item/lang | ru |  |
| Synonym/item/content | Форма списка |  |
| Comment | (пусто) |  |
| FormType | Managed |  |
| IncludeHelpInContents | false |  |
| UsePurposes/Value[1] | PlatformApplication | type=app:ApplicationUsePurpose |
| UsePurposes/Value[2] | MobilePlatformApplication | type=app:ApplicationUsePurpose |

## Внешние файлы

- [Ext/Form/Module.bsl](../src/Catalogs/мямЗначенияПоУмолчанию/Forms/ФормаСписка/Ext/Form/Module.bsl)
- [Ext/Form.xml](../src/Catalogs/мямЗначенияПоУмолчанию/Forms/ФормаСписка/Ext/Form.xml)

## Состав управляемой формы

Пути таблицы соответствуют вложенности редактора формы. Сохраните имена, DataPath, типы, события и действия команд; модуль формы подключается из внешнего файла.

| Свойство / путь | Значение | Атрибуты XML |
|---|---|---|
| AutoCommandBar/ChildItems/Button[1]/Type | CommandBarButton |  |
| AutoCommandBar/ChildItems/Button[1]/CommandName | Form.Command.УменьшитьКод |  |
| AutoCommandBar/ChildItems/Button[1]/ExtendedTooltip | (пусто) | name=ФормаПереместитьВверхРасширеннаяПодсказка, id=37 |
| AutoCommandBar/ChildItems/Button[2]/Type | CommandBarButton |  |
| AutoCommandBar/ChildItems/Button[2]/CommandName | Form.Command.УвеличитьКод |  |
| AutoCommandBar/ChildItems/Button[2]/ExtendedTooltip | (пусто) | name=ФормаПереместитьВнизРасширеннаяПодсказка, id=39 |
| ChildItems/UsualGroup/Title/item/lang | ru |  |
| ChildItems/UsualGroup/Title/item/content | Группа пользовательских настроек |  |
| ChildItems/UsualGroup/VerticalStretch | false |  |
| ChildItems/UsualGroup/Group | Vertical |  |
| ChildItems/UsualGroup/ShowTitle | false |  |
| ChildItems/UsualGroup/ExtendedTooltip | (пусто) | name=СписокКомпоновщикНастроекПользовательскиеНастройкиРасширеннаяПодсказка, id=2 |
| ChildItems/Table/Representation | List |  |
| ChildItems/Table/CommandBarLocation | None |  |
| ChildItems/Table/DefaultItem | true |  |
| ChildItems/Table/UseAlternationRowColor | true |  |
| ChildItems/Table/InitialTreeView | ExpandTopLevel |  |
| ChildItems/Table/EnableStartDrag | true |  |
| ChildItems/Table/DataPath | Список |  |
| ChildItems/Table/RowPictureDataPath | Список.DefaultPicture |  |
| ChildItems/Table/AutoRefresh | false |  |
| ChildItems/Table/AutoRefreshPeriod | 60 |  |
| ChildItems/Table/Period/variant | Custom | type=v8:StandardPeriodVariant |
| ChildItems/Table/Period/startDate | 0001-01-01T00:00:00 |  |
| ChildItems/Table/Period/endDate | 0001-01-01T00:00:00 |  |
| ChildItems/Table/ChoiceFoldersAndItems | Items |  |
| ChildItems/Table/RestoreCurrentRow | false |  |
| ChildItems/Table/TopLevelParent | (пусто) | nil=true |
| ChildItems/Table/ShowRoot | true |  |
| ChildItems/Table/AllowRootChoice | false |  |
| ChildItems/Table/UpdateOnDataChange | Auto |  |
| ChildItems/Table/UserSettingsGroup | СписокКомпоновщикНастроекПользовательскиеНастройки |  |
| ChildItems/Table/AllowGettingCurrentRowURL | true |  |
| ChildItems/Table/ContextMenu | (пусто) | name=СписокКонтекстноеМеню, id=4 |
| ChildItems/Table/AutoCommandBar/Autofill | false |  |
| ChildItems/Table/ExtendedTooltip | (пусто) | name=СписокРасширеннаяПодсказка, id=6 |
| ChildItems/Table/SearchStringAddition/AdditionSource/Item | Список |  |
| ChildItems/Table/SearchStringAddition/AdditionSource/Type | SearchStringRepresentation |  |
| ChildItems/Table/SearchStringAddition/AutoMaxWidth | false |  |
| ChildItems/Table/SearchStringAddition/ContextMenu | (пусто) | name=СписокСтрокаПоискаКонтекстноеМеню, id=8 |
| ChildItems/Table/SearchStringAddition/ExtendedTooltip | (пусто) | name=СписокСтрокаПоискаРасширеннаяПодсказка, id=9 |
| ChildItems/Table/ViewStatusAddition/AdditionSource/Item | Список |  |
| ChildItems/Table/ViewStatusAddition/AdditionSource/Type | ViewStatusRepresentation |  |
| ChildItems/Table/ViewStatusAddition/ContextMenu | (пусто) | name=СписокСостояниеПросмотраКонтекстноеМеню, id=11 |
| ChildItems/Table/ViewStatusAddition/ExtendedTooltip | (пусто) | name=СписокСостояниеПросмотраРасширеннаяПодсказка, id=12 |
| ChildItems/Table/SearchControlAddition/AdditionSource/Item | Список |  |
| ChildItems/Table/SearchControlAddition/AdditionSource/Type | SearchControl |  |
| ChildItems/Table/SearchControlAddition/ContextMenu | (пусто) | name=СписокУправлениеПоискомКонтекстноеМеню, id=14 |
| ChildItems/Table/SearchControlAddition/ExtendedTooltip | (пусто) | name=СписокУправлениеПоискомРасширеннаяПодсказка, id=15 |
| ChildItems/Table/ChildItems/LabelField[1]/DataPath | Список.Ref |  |
| ChildItems/Table/ChildItems/LabelField[1]/UserVisible/Common | false |  |
| ChildItems/Table/ChildItems/LabelField[1]/ContextMenu | (пусто) | name=СсылкаКонтекстноеМеню, id=17 |
| ChildItems/Table/ChildItems/LabelField[1]/ExtendedTooltip | (пусто) | name=СсылкаРасширеннаяПодсказка, id=18 |
| ChildItems/Table/ChildItems/LabelField[2]/DataPath | Список.Code |  |
| ChildItems/Table/ChildItems/LabelField[2]/DefaultItem | true |  |
| ChildItems/Table/ChildItems/LabelField[2]/ContextMenu | (пусто) | name=КодКонтекстноеМеню, id=20 |
| ChildItems/Table/ChildItems/LabelField[2]/ExtendedTooltip | (пусто) | name=КодРасширеннаяПодсказка, id=21 |
| ChildItems/Table/ChildItems/LabelField[3]/DataPath | Список.ЗаполняемыйРеквизит |  |
| ChildItems/Table/ChildItems/LabelField[3]/ContextMenu | (пусто) | name=ЗаполняемыйРеквизитКонтекстноеМеню, id=23 |
| ChildItems/Table/ChildItems/LabelField[3]/ExtendedTooltip | (пусто) | name=ЗаполняемыйРеквизитРасширеннаяПодсказка, id=24 |
| ChildItems/Table/ChildItems/ColumnGroup/Title/item/lang | ru |  |
| ChildItems/Table/ChildItems/ColumnGroup/Title/item/content | Значение настройки |  |
| ChildItems/Table/ChildItems/ColumnGroup/ToolTip/item/lang | ru |  |
| ChildItems/Table/ChildItems/ColumnGroup/ToolTip/item/content | Значение настройки |  |
| ChildItems/Table/ChildItems/ColumnGroup/Group | InCell |  |
| ChildItems/Table/ChildItems/ColumnGroup/ShowInHeader | true |  |
| ChildItems/Table/ChildItems/ColumnGroup/ExtendedTooltip | (пусто) | name=ГруппаЗначениеНастройкиРасширеннаяПодсказка, id=35 |
| ChildItems/Table/ChildItems/ColumnGroup/ChildItems/LabelField[1]/DataPath | Список.ЗначениеНастройки |  |
| ChildItems/Table/ChildItems/ColumnGroup/ChildItems/LabelField[1]/TitleLocation | None |  |
| ChildItems/Table/ChildItems/ColumnGroup/ChildItems/LabelField[1]/AutoCellHeight | true |  |
| ChildItems/Table/ChildItems/ColumnGroup/ChildItems/LabelField[1]/ShowInHeader | false |  |
| ChildItems/Table/ChildItems/ColumnGroup/ChildItems/LabelField[1]/ContextMenu | (пусто) | name=ЗначениеНастройкиКонтекстноеМеню, id=26 |
| ChildItems/Table/ChildItems/ColumnGroup/ChildItems/LabelField[1]/ExtendedTooltip | (пусто) | name=ЗначениеНастройкиРасширеннаяПодсказка, id=27 |
| ChildItems/Table/ChildItems/ColumnGroup/ChildItems/LabelField[2]/DataPath | Список.ЗначениеНастройкиСтрока |  |
| ChildItems/Table/ChildItems/ColumnGroup/ChildItems/LabelField[2]/TitleLocation | None |  |
| ChildItems/Table/ChildItems/ColumnGroup/ChildItems/LabelField[2]/ShowInHeader | false |  |
| ChildItems/Table/ChildItems/ColumnGroup/ChildItems/LabelField[2]/ContextMenu | (пусто) | name=ЗначениеНастройкиСтрокаКонтекстноеМеню, id=29 |
| ChildItems/Table/ChildItems/ColumnGroup/ChildItems/LabelField[2]/ExtendedTooltip | (пусто) | name=ЗначениеНастройкиСтрокаРасширеннаяПодсказка, id=30 |
| ChildItems/Table/ChildItems/LabelField[4]/DataPath | Список.КоличествоПовторов |  |
| ChildItems/Table/ChildItems/LabelField[4]/ContextMenu | (пусто) | name=КоличествоПовторовКонтекстноеМеню, id=32 |
| ChildItems/Table/ChildItems/LabelField[4]/ExtendedTooltip | (пусто) | name=КоличествоПовторовРасширеннаяПодсказка, id=33 |
| Attributes/Attribute/Type/Type | cfg:DynamicList |  |
| Attributes/Attribute/MainAttribute | true |  |
| Attributes/Attribute/UseAlways/Field | Список.Ref |  |
| Attributes/Attribute/Settings/ManualQuery | false |  |
| Attributes/Attribute/Settings/DynamicDataRead | true |  |
| Attributes/Attribute/Settings/MainTable | Catalog.мямЗначенияПоУмолчанию |  |
| Attributes/Attribute/Settings/ListSettings/filter/viewMode | Normal |  |
| Attributes/Attribute/Settings/ListSettings/filter/userSettingID | dfcece9d-5077-440b-b6b3-45a5cb4538eb |  |
| Attributes/Attribute/Settings/ListSettings/order/item/field | Код |  |
| Attributes/Attribute/Settings/ListSettings/order/item/orderType | Asc |  |
| Attributes/Attribute/Settings/ListSettings/order/viewMode | Normal |  |
| Attributes/Attribute/Settings/ListSettings/order/userSettingID | 88619765-ccb3-46c6-ac52-38e9c992ebd4 |  |
| Attributes/Attribute/Settings/ListSettings/conditionalAppearance/viewMode | Normal |  |
| Attributes/Attribute/Settings/ListSettings/conditionalAppearance/userSettingID | b75fecce-942b-4aed-abc9-e6a02e460fb3 |  |
| Attributes/Attribute/Settings/ListSettings/itemsViewMode | Normal |  |
| Attributes/Attribute/Settings/ListSettings/itemsUserSettingID | 911b6018-f537-43e8-a417-da56b22f9aec |  |
| Commands/Command[1]/Title/item/lang | ru |  |
| Commands/Command[1]/Title/item/content | Уменьшить код |  |
| Commands/Command[1]/ToolTip/item/lang | ru |  |
| Commands/Command[1]/ToolTip/item/content | Уменьшить код |  |
| Commands/Command[1]/Picture/Ref | StdPicture.MoveUp |  |
| Commands/Command[1]/Picture/LoadTransparent | true |  |
| Commands/Command[1]/Action | УменьшитьКод |  |
| Commands/Command[1]/Representation | Picture |  |
| Commands/Command[2]/Title/item/lang | ru |  |
| Commands/Command[2]/Title/item/content | Увеличить код |  |
| Commands/Command[2]/ToolTip/item/lang | ru |  |
| Commands/Command[2]/ToolTip/item/content | Увеличить код |  |
| Commands/Command[2]/Picture/Ref | StdPicture.MoveDown |  |
| Commands/Command[2]/Picture/LoadTransparent | true |  |
| Commands/Command[2]/Action | УвеличитьКод |  |
| Commands/Command[2]/Representation | Picture |  |

Контекст процедур задаётся директивами &НаКлиенте / &НаСервере в связанном модуле; серверные запросы выполняются без повышения привилегий.
