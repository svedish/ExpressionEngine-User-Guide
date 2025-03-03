<!--
    This source file is part of the open source project
    ExpressionEngine User Guide (https://github.com/ExpressionEngine/ExpressionEngine-User-Guide)

    @link      https://expressionengine.com/
    @copyright Copyright (c) 2003-2020, Packet Tide, LLC (https://packettide.com)
    @license   https://expressionengine.com/license Licensed under Apache License, Version 2.0
-->

# Radio Buttons Fieldtype

[TOC]

Radio Buttons allow users to choose a single item from a list of options. 

![radio field](_images/cp-field-radio.png)

## Field Settings

{{embed:fieldtypes/_fieldtype-settings.md}}

### Text Formatting

Specifies how the entered-text will be formatted when rendered on the front-end. Most items will be entered will be single-lined and thus treated as a single paragraph by most text-processing plugins.

### Radio Options

This is where the list of items to select from is created. You have several ways to populate these items.

#### Value/Label pairs

The default choice is to enter a series of values and labels separately. Typically when constructing an HTML form, fields will have a different value than their presentation label. For example, if you want to enable the author to choose from a list of numbers, you might want the database to represent the actual numerical value:

![](_images/valuelabel1.png)

For a Radio Buttons field this results in an interface with only the labels visible:

![radio field](_images/cp-field-radio.png)

`1`, `2`, or `3` is what gets stored in the database and is then the value used for the Channel Entries tag [search parameter](channels/entries.md#searchfield_name). But both the value and the label are accessible via the field's template tags, which is outlined below.

{{embed:fieldtypes/_selectable_field_options.md}}


## Template Tags

A Radio Button field's value can be rendered in a template using a single variable with the field's name. To specifically display the field's value or label, use the respective modifier:

    Value: {field_name}<br>
    Value: {field_name:value}<br>
    Label: {field_name:label}<br>

In all cases, these variables are also available as conditionals. Let's say you had the following value/label options:

| Value | Label |
| :---- | :---- |
| 1     | One   |
| 2     | Two   |
| 3     | Three |

Given that the selection option is 2/Two:

    {if field_name == 2}Yep!{/if}
    {if field_name:value == 2}Yep!{/if}
    {if field_name:label == 'Two'}Yep!{/if}

TIP: **Tip:** It is recommended that you use the value in conditionals, as it typically will not change over time. That way, if you ever need to change the wording, spelling, or even casing of labels in your publish/edit UI, you will not need to modify your templates.