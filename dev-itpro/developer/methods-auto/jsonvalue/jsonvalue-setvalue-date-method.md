---
title: "JsonValue.SetValue Method"
ms.author: solsen
ms.custom: na
ms.date: 04/01/2021
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: reference
ms.service: "dynamics365-business-central"
author: SusanneWindfeldPedersen
---
[//]: # (START>DO_NOT_EDIT)
[//]: # (IMPORTANT:Do not edit any of the content between here and the END>DO_NOT_EDIT.)
[//]: # (Any modifications should be made in the .xml files in the ModernDev repo.)
# JsonValue.SetValue Method
> **Version**: _Available or changed with runtime version 1.0._

Set the contents of the JsonValue variable to the JSON representation of the given value.


## Syntax
```
 JsonValue.SetValue(Value: Date)
```
## Parameters
*JsonValue*
&emsp;Type: [JsonValue](jsonvalue-data-type.md)
An instance of the [JsonValue](jsonvalue-data-type.md) data type.

*Value*  
&emsp;Type: [Date](../date/date-data-type.md)  
  



[//]: # (IMPORTANT: END>DO_NOT_EDIT)

## Remarks 
- When Value is a Date type, it will be serialized in the format yyyy-MM-dd (as described in Custom Date and Time Format Strings).
- The JsonValue will be disconnected from its current JSON tree and the data contained by the JsonValue will be replaced with the new value.

## See Also
[JsonValue Data Type](jsonvalue-data-type.md)  
[Getting Started with AL](../../devenv-get-started.md)  
[Developing Extensions](../../devenv-dev-overview.md)