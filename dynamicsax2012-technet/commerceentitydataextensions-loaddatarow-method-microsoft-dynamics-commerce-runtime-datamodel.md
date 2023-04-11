---
title: CommerceEntityDataExtensions.LoadDataRow Method  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LoadDataRow Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntityDataExtensions.LoadDataRow(Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntity,Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataRow,System.TimeSpan)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.commerceentitydataextensions.loaddatarow(v=AX.60)
ms:contentKeyID: 65319888
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntityDataExtensions.LoadDataRow
dev_langs:
- CSharp
- C++
- VB
---

# LoadDataRow Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Loads the data row into the entity property bag.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Data (in Microsoft.Dynamics.Commerce.Runtime.Data.dll)

## Syntax

``` vb
'Declaration
<ExtensionAttribute> _
Public Shared Sub LoadDataRow ( _
    entity As CommerceEntity, _
    row As DataRow, _
    timeZoneOffset As TimeSpan _
)
'Usage
Dim entity As CommerceEntity
Dim row As DataRow
Dim timeZoneOffset As TimeSpan

entity.LoadDataRow(row, timeZoneOffset)
```

``` csharp
public static void LoadDataRow(
    this CommerceEntity entity,
    DataRow row,
    TimeSpan timeZoneOffset
)
```

``` c++
[ExtensionAttribute]
public:
static void LoadDataRow(
    CommerceEntity^ entity, 
    DataRow^ row, 
    TimeSpan timeZoneOffset
)
```

#### Parameters

  - entity  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntity](commerceentity-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - row  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataRow](datarow-class-microsoft-dynamics-commerce-runtime-data-types.md)  

<!-- end list -->

  - timeZoneOffset  
    Type: [System.TimeSpan](https://technet.microsoft.com/library/269ew577\(v=ax.60\))  

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [CommerceEntity](commerceentity-class-microsoft-dynamics-commerce-runtime-datamodel.md). When you use instance method syntax to call this method, omit the first parameter. For more information, see b8020aae-374d-46a9-bcb7-8cc2390b93b6 or 175ce3ff-9bbf-4e64-8421-faeb81a0bb51.

## See Also

#### Reference

[CommerceEntityDataExtensions Class](commerceentitydataextensions-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

