---
title: ChargeConfigurationHeader Class (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ChargeConfigurationHeader Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeConfigurationHeader
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.chargeconfigurationheader(v=AX.60)
ms:contentKeyID: 49832328
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeConfigurationHeader
dev_langs:
- CSharp
- C++
- VB
---

# ChargeConfigurationHeader Class

This class is used as a filter API for specifying which auto charge configurations will be retrieved from the DB. Auto-charge headers have account, item, and delivery mode settings on them. Any type here which is not set to 'None' will be used as a filter for retrieving any charge configurations which meet that criteria.

For example: Setting AccountType=All, ItemType=Item, ItemRelation="1000", will retrieve all auto-charges for any customer on item 1000.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Class ChargeConfigurationHeader
'Usage
Dim instance As ChargeConfigurationHeader
```

``` csharp
public class ChargeConfigurationHeader
```

``` c++
public ref class ChargeConfigurationHeader
```

## Remarks

This is not an entity which is retrieved from the database.

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeConfigurationHeader  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

