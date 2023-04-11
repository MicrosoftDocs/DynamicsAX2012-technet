---
title: CommerceEntityDataExtensions.Populate Method  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Populate Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntityDataExtensions.Populate(Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntity,Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseResult,System.Collections.Generic.List{Microsoft.Dynamics.Commerce.Runtime.DataModel.TimeZoneInterval})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.commerceentitydataextensions.populate(v=AX.60)
ms:contentKeyID: 65321431
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntityDataExtensions.Populate
dev_langs:
- CSharp
- C++
- VB
---

# Populate Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Populates the entity property bag using the specified SQL data reader.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Data (in Microsoft.Dynamics.Commerce.Runtime.Data.dll)

## Syntax

``` vb
'Declaration
<ExtensionAttribute> _
Public Shared Sub Populate ( _
    entity As CommerceEntity, _
    databaseResult As IDatabaseResult, _
    channelTimeZoneRecords As List(Of TimeZoneInterval) _
)
'Usage
Dim entity As CommerceEntity
Dim databaseResult As IDatabaseResult
Dim channelTimeZoneRecords As List(Of TimeZoneInterval)

entity.Populate(databaseResult, channelTimeZoneRecords)
```

``` csharp
public static void Populate(
    this CommerceEntity entity,
    IDatabaseResult databaseResult,
    List<TimeZoneInterval> channelTimeZoneRecords
)
```

``` c++
[ExtensionAttribute]
public:
static void Populate(
    CommerceEntity^ entity, 
    IDatabaseResult^ databaseResult, 
    List<TimeZoneInterval^>^ channelTimeZoneRecords
)
```

#### Parameters

  - entity  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntity](commerceentity-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - databaseResult  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseResult](idatabaseresult-interface-microsoft-dynamics-commerce-runtime-data.md)  

<!-- end list -->

  - channelTimeZoneRecords  
    Type: [System.Collections.Generic.List](https://technet.microsoft.com/library/6sh2ey19\(v=ax.60\))\<[TimeZoneInterval](timezoneinterval-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [CommerceEntity](commerceentity-class-microsoft-dynamics-commerce-runtime-datamodel.md). When you use instance method syntax to call this method, omit the first parameter. For more information, see b8020aae-374d-46a9-bcb7-8cc2390b93b6 or 175ce3ff-9bbf-4e64-8421-faeb81a0bb51.

## See Also

#### Reference

[CommerceEntityDataExtensions Class](commerceentitydataextensions-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

