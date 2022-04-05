# Interface: InteractionOptionsRequest

[grist-plugin-api](../modules/grist_plugin_api.md).InteractionOptionsRequest

Initial message sent by the CustomWidget with initial requirements.

## Table of contents

### Properties

- [columns](grist_plugin_api.interactionoptionsrequest.md#columns)
- [hasCustomOptions](grist_plugin_api.interactionoptionsrequest.md#hascustomoptions)
- [requiredAccess](grist_plugin_api.interactionoptionsrequest.md#requiredaccess)

## Properties

### columns

• `Optional` **columns**: `ColumnsToMap`

Tells Grist what columns Custom Widget expects and allows user to map between existing column names
and those requested by Custom Widget.

___

### hasCustomOptions

• `Optional` **hasCustomOptions**: `boolean`

Instructs Grist to show additional menu options that will trigger onEditOptions callback, that Widget
can use to show custom options screen.

___

### requiredAccess

• `Optional` **requiredAccess**: `string`

Required access level. If it wasn't granted already, Grist will prompt user to change the current access
level.