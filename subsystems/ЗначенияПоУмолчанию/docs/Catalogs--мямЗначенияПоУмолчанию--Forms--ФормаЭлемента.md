# Form.ФормаЭлемента

[← Подсистема](../README.md) · [XML](../src/Catalogs/мямЗначенияПоУмолчанию/Forms/ФормаЭлемента.xml)

UUID образца: `201e1907-4aaf-4b6d-a4c9-70dba11884b2`. Формат XML: `2.20`. UUID не менялись; это фрагмент выгрузки, а не полная конфигурация.

## Свойства

| Свойство / путь | Значение | Атрибуты XML |
|---|---|---|
| Name | ФормаЭлемента |  |
| Synonym/item/lang | ru |  |
| Synonym/item/content | Форма элемента |  |
| Comment | (пусто) |  |
| FormType | Managed |  |
| IncludeHelpInContents | false |  |
| UsePurposes/Value[1] | PlatformApplication | type=app:ApplicationUsePurpose |
| UsePurposes/Value[2] | MobilePlatformApplication | type=app:ApplicationUsePurpose |

## Внешние файлы

- [Ext/Form/Module.bsl](../src/Catalogs/мямЗначенияПоУмолчанию/Forms/ФормаЭлемента/Ext/Form/Module.bsl)
- [Ext/Form.xml](../src/Catalogs/мямЗначенияПоУмолчанию/Forms/ФормаЭлемента/Ext/Form.xml)

## Состав управляемой формы

Пути таблицы соответствуют вложенности редактора формы. Сохраните имена, DataPath, типы, события и действия команд; модуль формы подключается из внешнего файла.

| Свойство / путь | Значение | Атрибуты XML |
|---|---|---|
| WindowOpeningMode | LockOwnerWindow |  |
| UseForFoldersAndItems | Items |  |
| AutoCommandBar | (пусто) | name=ФормаКоманднаяПанель, id=-1 |
| Events/Event | ПриОткрытии | name=OnOpen |
| ChildItems/UsualGroup[1]/Title/item/lang | ru |  |
| ChildItems/UsualGroup[1]/Title/item/content | Группа код |  |
| ChildItems/UsualGroup[1]/ToolTip/item/lang | ru |  |
| ChildItems/UsualGroup[1]/ToolTip/item/content | Группа код |  |
| ChildItems/UsualGroup[1]/Representation | None |  |
| ChildItems/UsualGroup[1]/ShowTitle | false |  |
| ChildItems/UsualGroup[1]/ExtendedTooltip | (пусто) | name=ГруппаКодРасширеннаяПодсказка, id=25 |
| ChildItems/UsualGroup[1]/ChildItems/InputField/DataPath | Объект.Code |  |
| ChildItems/UsualGroup[1]/ChildItems/InputField/ReadOnly | true |  |
| ChildItems/UsualGroup[1]/ChildItems/InputField/EditMode | EnterOnInput |  |
| ChildItems/UsualGroup[1]/ChildItems/InputField/AutoMaxWidth | false |  |
| ChildItems/UsualGroup[1]/ChildItems/InputField/HorizontalStretch | true |  |
| ChildItems/UsualGroup[1]/ChildItems/InputField/ExtendedEditMultipleValues | true |  |
| ChildItems/UsualGroup[1]/ChildItems/InputField/ContextMenu | (пусто) | name=КодКонтекстноеМеню, id=2 |
| ChildItems/UsualGroup[1]/ChildItems/InputField/ExtendedTooltip | (пусто) | name=КодРасширеннаяПодсказка, id=3 |
| ChildItems/UsualGroup[1]/ChildItems/Button/Type | UsualButton |  |
| ChildItems/UsualGroup[1]/ChildItems/Button/CommandName | Form.Command.РедактироватьКод |  |
| ChildItems/UsualGroup[1]/ChildItems/Button/ExtendedTooltip | (пусто) | name=РедактироватьКодРасширеннаяПодсказка, id=27 |
| ChildItems/InputField[1]/DataPath | Объект.ЗаполняемыйРеквизит |  |
| ChildItems/InputField[1]/EditMode | EnterOnInput |  |
| ChildItems/InputField[1]/AutoMaxWidth | false |  |
| ChildItems/InputField[1]/HorizontalStretch | true |  |
| ChildItems/InputField[1]/ChoiceButton | true |  |
| ChildItems/InputField[1]/ClearButton | true |  |
| ChildItems/InputField[1]/ExtendedEditMultipleValues | true |  |
| ChildItems/InputField[1]/ContextMenu | (пусто) | name=ЗаполняемыйРеквизитКонтекстноеМеню, id=5 |
| ChildItems/InputField[1]/ExtendedTooltip | (пусто) | name=ЗаполняемыйРеквизитРасширеннаяПодсказка, id=6 |
| ChildItems/InputField[1]/Events/Event[1] | ЗаполняемыйРеквизитНачалоВыбора | name=StartChoice |
| ChildItems/InputField[1]/Events/Event[2] | ЗаполняемыйРеквизитОчистка | name=Clearing |
| ChildItems/InputField[1]/Events/Event[3] | ЗаполняемыйРеквизитОбработкаВыбора | name=ChoiceProcessing |
| ChildItems/UsualGroup[2]/Title/item/lang | ru |  |
| ChildItems/UsualGroup[2]/Title/item/content | Значение реквизита |  |
| ChildItems/UsualGroup[2]/ToolTip/item/lang | ru |  |
| ChildItems/UsualGroup[2]/ToolTip/item/content | Группа значение реквизита |  |
| ChildItems/UsualGroup[2]/Group | Vertical |  |
| ChildItems/UsualGroup[2]/Representation | None |  |
| ChildItems/UsualGroup[2]/ShowTitle | false |  |
| ChildItems/UsualGroup[2]/ExtendedTooltip | (пусто) | name=ГруппаЗначениеРеквизитаРасширеннаяПодсказка, id=17 |
| ChildItems/UsualGroup[2]/ChildItems/InputField[1]/DataPath | ПустоеЗначениеНастройки |  |
| ChildItems/UsualGroup[2]/ChildItems/InputField[1]/ReadOnly | true |  |
| ChildItems/UsualGroup[2]/ChildItems/InputField[1]/AutoMaxWidth | false |  |
| ChildItems/UsualGroup[2]/ChildItems/InputField[1]/HorizontalStretch | true |  |
| ChildItems/UsualGroup[2]/ChildItems/InputField[1]/ChoiceButton | true |  |
| ChildItems/UsualGroup[2]/ChildItems/InputField[1]/ClearButton | true |  |
| ChildItems/UsualGroup[2]/ChildItems/InputField[1]/ExtendedEditMultipleValues | true |  |
| ChildItems/UsualGroup[2]/ChildItems/InputField[1]/ContextMenu | (пусто) | name=ПустоеЗначениеНастройкиКонтекстноеМеню, id=22 |
| ChildItems/UsualGroup[2]/ChildItems/InputField[1]/ExtendedTooltip | (пусто) | name=ПустоеЗначениеНастройкиРасширеннаяПодсказка, id=23 |
| ChildItems/UsualGroup[2]/ChildItems/InputField[2]/DataPath | Объект.ЗначениеНастройки |  |
| ChildItems/UsualGroup[2]/ChildItems/InputField[2]/Visible | false |  |
| ChildItems/UsualGroup[2]/ChildItems/InputField[2]/EditMode | EnterOnInput |  |
| ChildItems/UsualGroup[2]/ChildItems/InputField[2]/AutoMaxWidth | false |  |
| ChildItems/UsualGroup[2]/ChildItems/InputField[2]/Height | 1 |  |
| ChildItems/UsualGroup[2]/ChildItems/InputField[2]/HorizontalStretch | true |  |
| ChildItems/UsualGroup[2]/ChildItems/InputField[2]/MultiLine | true |  |
| ChildItems/UsualGroup[2]/ChildItems/InputField[2]/ExtendedEdit | true |  |
| ChildItems/UsualGroup[2]/ChildItems/InputField[2]/ClearButton | true |  |
| ChildItems/UsualGroup[2]/ChildItems/InputField[2]/ExtendedEditMultipleValues | true |  |
| ChildItems/UsualGroup[2]/ChildItems/InputField[2]/ContextMenu | (пусто) | name=ЗначениеНастройкиКонтекстноеМеню, id=8 |
| ChildItems/UsualGroup[2]/ChildItems/InputField[2]/ExtendedTooltip | (пусто) | name=ЗначениеНастройкиРасширеннаяПодсказка, id=9 |
| ChildItems/UsualGroup[2]/ChildItems/InputField[3]/DataPath | Объект.ЗначениеНастройкиСтрока |  |
| ChildItems/UsualGroup[2]/ChildItems/InputField[3]/Visible | false |  |
| ChildItems/UsualGroup[2]/ChildItems/InputField[3]/EditMode | EnterOnInput |  |
| ChildItems/UsualGroup[2]/ChildItems/InputField[3]/AutoMaxWidth | false |  |
| ChildItems/UsualGroup[2]/ChildItems/InputField[3]/Height | 1 |  |
| ChildItems/UsualGroup[2]/ChildItems/InputField[3]/HorizontalStretch | true |  |
| ChildItems/UsualGroup[2]/ChildItems/InputField[3]/ChoiceButton | true |  |
| ChildItems/UsualGroup[2]/ChildItems/InputField[3]/ClearButton | true |  |
| ChildItems/UsualGroup[2]/ChildItems/InputField[3]/ExtendedEditMultipleValues | true |  |
| ChildItems/UsualGroup[2]/ChildItems/InputField[3]/ContextMenu | (пусто) | name=ЗначениеНастройкиСтрокаКонтекстноеМеню, id=11 |
| ChildItems/UsualGroup[2]/ChildItems/InputField[3]/ExtendedTooltip | (пусто) | name=ЗначениеНастройкиСтрокаРасширеннаяПодсказка, id=12 |
| ChildItems/UsualGroup[2]/ChildItems/InputField[3]/Events/Event | ЗначениеНастройкиСтрокаНачалоВыбора | name=StartChoice |
| ChildItems/InputField[2]/DataPath | Объект.КоличествоПовторов |  |
| ChildItems/InputField[2]/EditMode | EnterOnInput |  |
| ChildItems/InputField[2]/AutoMaxWidth | false |  |
| ChildItems/InputField[2]/HorizontalStretch | true |  |
| ChildItems/InputField[2]/SpinButton | true |  |
| ChildItems/InputField[2]/ExtendedEditMultipleValues | true |  |
| ChildItems/InputField[2]/MinValue | 1 | type=xs:decimal |
| ChildItems/InputField[2]/ContextMenu | (пусто) | name=КоличествоПовторовКонтекстноеМеню, id=14 |
| ChildItems/InputField[2]/ExtendedTooltip | (пусто) | name=КоличествоПовторовРасширеннаяПодсказка, id=15 |
| ChildItems/InputField[2]/Events/Event | КоличествоПовторовПриИзменении | name=OnChange |
| Attributes/Attribute[1]/Type/Type | cfg:CatalogObject.мямЗначенияПоУмолчанию |  |
| Attributes/Attribute[1]/MainAttribute | true |  |
| Attributes/Attribute[1]/SavedData | true |  |
| Attributes/Attribute[2]/Title/item/lang | ru |  |
| Attributes/Attribute[2]/Title/item/content | Значение настройки |  |
| Attributes/Attribute[2]/Type/Type | xs:string |  |
| Attributes/Attribute[2]/Type/StringQualifiers/Length | 0 |  |
| Attributes/Attribute[2]/Type/StringQualifiers/AllowedLength | Variable |  |
| Commands/Command/Title/item/lang | ru |  |
| Commands/Command/Title/item/content | Редактировать код |  |
| Commands/Command/ToolTip/item/lang | ru |  |
| Commands/Command/ToolTip/item/content | Редактировать код |  |
| Commands/Command/Picture/Ref | StdPicture.Change |  |
| Commands/Command/Picture/LoadTransparent | true |  |
| Commands/Command/Action | РедактироватьКод |  |
| Commands/Command/Representation | Picture |  |

Контекст процедур задаётся директивами &НаКлиенте / &НаСервере в связанном модуле; серверные запросы выполняются без повышения привилегий.
