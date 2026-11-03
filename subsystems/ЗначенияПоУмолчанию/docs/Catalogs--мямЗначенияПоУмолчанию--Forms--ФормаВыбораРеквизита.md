# Form.ФормаВыбораРеквизита

[← Подсистема](../README.md) · [XML](../src/Catalogs/мямЗначенияПоУмолчанию/Forms/ФормаВыбораРеквизита.xml)

UUID образца: `5effb882-b057-4420-ab0c-1c6208066f89`. Формат XML: `2.20`. UUID не менялись; это фрагмент выгрузки, а не полная конфигурация.

## Свойства

| Свойство / путь | Значение | Атрибуты XML |
|---|---|---|
| Name | ФормаВыбораРеквизита |  |
| Synonym/item/lang | ru |  |
| Synonym/item/content | Форма выбора реквизита |  |
| Comment | (пусто) |  |
| FormType | Managed |  |
| IncludeHelpInContents | false |  |
| UsePurposes/Value[1] | PlatformApplication | type=app:ApplicationUsePurpose |
| UsePurposes/Value[2] | MobilePlatformApplication | type=app:ApplicationUsePurpose |

## Внешние файлы

- [Ext/Form/Module.bsl](../src/Catalogs/мямЗначенияПоУмолчанию/Forms/ФормаВыбораРеквизита/Ext/Form/Module.bsl)
- [Ext/Form.xml](../src/Catalogs/мямЗначенияПоУмолчанию/Forms/ФормаВыбораРеквизита/Ext/Form.xml)

## Состав управляемой формы

Пути таблицы соответствуют вложенности редактора формы. Сохраните имена, DataPath, типы, события и действия команд; модуль формы подключается из внешнего файла.

| Свойство / путь | Значение | Атрибуты XML |
|---|---|---|
| Title/item/lang | ru |  |
| Title/item/content | Выбор заполняемого реквизита |  |
| WindowOpeningMode | LockOwnerWindow |  |
| AutoTitle | false |  |
| CommandBarLocation | Bottom |  |
| AutoCommandBar/HorizontalAlign | Right |  |
| AutoCommandBar/Autofill | false |  |
| AutoCommandBar/ChildItems/Button[1]/Type | CommandBarButton |  |
| AutoCommandBar/ChildItems/Button[1]/DefaultButton | true |  |
| AutoCommandBar/ChildItems/Button[1]/CommandName | Form.Command.Выбрать |  |
| AutoCommandBar/ChildItems/Button[1]/ExtendedTooltip | (пусто) | name=ФормаВыбратьРасширеннаяПодсказка, id=11 |
| AutoCommandBar/ChildItems/Button[2]/Type | CommandBarButton |  |
| AutoCommandBar/ChildItems/Button[2]/CommandName | Form.StandardCommand.Close |  |
| AutoCommandBar/ChildItems/Button[2]/BackColor | #CCFFFF |  |
| AutoCommandBar/ChildItems/Button[2]/Font | (пусто) | ref=style:NormalTextFont, bold=true, italic=false, underline=false, strikeout=false, kind=StyleItem, scale=100 |
| AutoCommandBar/ChildItems/Button[2]/ExtendedTooltip | (пусто) | name=ФормаЗакрытьРасширеннаяПодсказка, id=13 |
| Events/Event[1] | ПриСозданииНаСервере | name=OnCreateAtServer |
| Events/Event[2] | ПриЗакрытии | name=OnClose |
| ChildItems/InputField[1]/DataPath | ОбъектМетаданных |  |
| ChildItems/InputField[1]/EditMode | EnterOnInput |  |
| ChildItems/InputField[1]/AutoMaxWidth | false |  |
| ChildItems/InputField[1]/HorizontalStretch | true |  |
| ChildItems/InputField[1]/DropListButton | true |  |
| ChildItems/InputField[1]/ListChoiceMode | true |  |
| ChildItems/InputField[1]/ExtendedEditMultipleValues | true |  |
| ChildItems/InputField[1]/ChooseType | false |  |
| ChildItems/InputField[1]/EditTextUpdate | OnValueChange |  |
| ChildItems/InputField[1]/ContextMenu | (пусто) | name=ОбъектМетаданныхКонтекстноеМеню, id=2 |
| ChildItems/InputField[1]/ExtendedTooltip | (пусто) | name=ОбъектМетаданныхРасширеннаяПодсказка, id=3 |
| ChildItems/InputField[1]/Events/Event[1] | ОбъектМетаданныхПриИзменении | name=OnChange |
| ChildItems/InputField[1]/Events/Event[2] | ОбъектМетаданныхАвтоПодбор | name=AutoComplete |
| ChildItems/InputField[1]/Events/Event[3] | ОбъектМетаданныхОчистка | name=Clearing |
| ChildItems/InputField[2]/DataPath | ЗаполняемыйРеквизит |  |
| ChildItems/InputField[2]/EditMode | EnterOnInput |  |
| ChildItems/InputField[2]/AutoMaxWidth | false |  |
| ChildItems/InputField[2]/HorizontalStretch | true |  |
| ChildItems/InputField[2]/DropListButton | true |  |
| ChildItems/InputField[2]/ListChoiceMode | true |  |
| ChildItems/InputField[2]/ExtendedEditMultipleValues | true |  |
| ChildItems/InputField[2]/ChooseType | false |  |
| ChildItems/InputField[2]/EditTextUpdate | OnValueChange |  |
| ChildItems/InputField[2]/ContextMenu | (пусто) | name=ЗаполняемыйРеквизитКонтекстноеМеню, id=5 |
| ChildItems/InputField[2]/ExtendedTooltip | (пусто) | name=ЗаполняемыйРеквизитРасширеннаяПодсказка, id=6 |
| ChildItems/InputField[2]/Events/Event[1] | ЗаполняемыйРеквизитПриИзменении | name=OnChange |
| ChildItems/InputField[2]/Events/Event[2] | ЗаполняемыйРеквизитАвтоПодбор | name=AutoComplete |
| ChildItems/InputField[2]/Events/Event[3] | ЗаполняемыйРеквизитОчистка | name=Clearing |
| ChildItems/LabelField/DataPath | Представление |  |
| ChildItems/LabelField/TitleLocation | None |  |
| ChildItems/LabelField/AutoMaxWidth | false |  |
| ChildItems/LabelField/HorizontalStretch | true |  |
| ChildItems/LabelField/ContextMenu | (пусто) | name=ПредставлениеКонтекстноеМеню, id=8 |
| ChildItems/LabelField/ExtendedTooltip | (пусто) | name=ПредставлениеРасширеннаяПодсказка, id=9 |
| Attributes/Attribute[1]/Title/item/lang | ru |  |
| Attributes/Attribute[1]/Title/item/content | Объект метаданных |  |
| Attributes/Attribute[1]/Type/Type | xs:string |  |
| Attributes/Attribute[1]/Type/StringQualifiers/Length | 0 |  |
| Attributes/Attribute[1]/Type/StringQualifiers/AllowedLength | Variable |  |
| Attributes/Attribute[2]/Title/item/lang | ru |  |
| Attributes/Attribute[2]/Title/item/content | Заполняемый реквизит |  |
| Attributes/Attribute[2]/Type/Type | xs:string |  |
| Attributes/Attribute[2]/Type/StringQualifiers/Length | 0 |  |
| Attributes/Attribute[2]/Type/StringQualifiers/AllowedLength | Variable |  |
| Attributes/Attribute[3]/Title/item/lang | ru |  |
| Attributes/Attribute[3]/Title/item/content | Представление |  |
| Attributes/Attribute[3]/Type/Type | xs:string |  |
| Attributes/Attribute[3]/Type/StringQualifiers/Length | 0 |  |
| Attributes/Attribute[3]/Type/StringQualifiers/AllowedLength | Variable |  |
| Commands/Command/Title/item/lang | ru |  |
| Commands/Command/Title/item/content | Выбрать |  |
| Commands/Command/ToolTip/item/lang | ru |  |
| Commands/Command/ToolTip/item/content | Выбрать |  |
| Commands/Command/Action | Выбрать |  |

Контекст процедур задаётся директивами &НаКлиенте / &НаСервере в связанном модуле; серверные запросы выполняются без повышения привилегий.
