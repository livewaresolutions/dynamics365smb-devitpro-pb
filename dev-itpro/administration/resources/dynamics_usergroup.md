---
title: userGroup resource type | Microsoft Docs
description: An user group object in Dynamics 365 Business Central.
author: SusanneWindfeldPedersen
ms.service: "dynamics365-business-central"
ms.topic: reference
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.date: 04/01/2021
ms.author: solsen
---

# userGroup resource type

<!-- START>DO_NOT_EDIT -->
<!-- IMPORTANT:Do not edit any of the content between here and the END>DO_NOT_EDIT. -->
Represents an user group in [!INCLUDE[d365fin_long_md](../../includes/d365fin_long_md.md)].

> [!NOTE]
> For information about enabling APIs for [!INCLUDE [prod_short](../../includes/prod_short.md)] see [Enabling the APIs for Dynamics 365 Business Central](/dynamics365/dynamics-nav/api-reference/v2.0/enabling-apis-for-dynamics-nav).


## Methods

| Method | Return Type|Description |
|:--------------------|:-----------|:-------------------------|
|[GET userGroup](../api/dynamics_usergroup_get.md)|userGroup|Gets a user group object.|
|[PATCH userGroup](../api/dynamics_usergroup_update.md)|userGroup|Updates a user group object.|



## Properties

| Property           | Type   |Description     |
|:-------------------|:-------|:---------------|
|id|GUID|The unique ID of the user group. Non-editable.|
|code|string|The code of the user group.|
|displayName|string|Specifies the user group's name. This name will appear on all sales documents for the user group.|
|defaultProfileID|string|The ID of the defaultProfile.|
|assignToAllNewUsers|boolean|If true, all new users are assigned to user group.|

## JSON representation

Here is a JSON representation of the userGroup resource.


```json
{
    "id": "GUID",
    "code": "string",
    "displayName": "string",
    "defaultProfileID": "string",
    "assignToAllNewUsers": "boolean"
}
```
<!-- IMPORTANT: END>DO_NOT_EDIT -->

## See Also
[GET userGroup](../api/dynamics_usergroup_get.md)  
[PATCH userGroup](../api/dynamics_usergroup_update.md)  
