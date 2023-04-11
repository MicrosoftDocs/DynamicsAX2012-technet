---
title: IChannelDataManager.GetChannelCategoryAttributesByChannelId Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetChannelCategoryAttributesByChannelId Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.IChannelDataManager.GetChannelCategoryAttributesByChannelId(System.Int64,System.Collections.Generic.IEnumerable{System.Int64},Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.ichanneldatamanager.getchannelcategoryattributesbychannelid(v=AX.60)
ms:contentKeyID: 65315917
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.IChannelDataManager.GetChannelCategoryAttributesByChannelId
dev_langs:
- CSharp
- C++
- VB
---

# GetChannelCategoryAttributesByChannelId Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Function GetChannelCategoryAttributesByChannelId ( _
    channelId As Long, _
    categoryIds As IEnumerable(Of Long), _
    settings As QueryResultSettings _
) As ReadOnlyCollection(Of AttributeCategory)
'Usage
Dim instance As IChannelDataManager
Dim channelId As Long
Dim categoryIds As IEnumerable(Of Long)
Dim settings As QueryResultSettings
Dim returnValue As ReadOnlyCollection(Of AttributeCategory)

returnValue = instance.GetChannelCategoryAttributesByChannelId(channelId, _
    categoryIds, settings)
```

``` csharp
ReadOnlyCollection<AttributeCategory> GetChannelCategoryAttributesByChannelId(
    long channelId,
    IEnumerable<long> categoryIds,
    QueryResultSettings settings
)
```

``` c++
ReadOnlyCollection<AttributeCategory^>^ GetChannelCategoryAttributesByChannelId(
    long long channelId, 
    IEnumerable<long long>^ categoryIds, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - channelId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - categoryIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[AttributeCategory](attributecategory-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[IChannelDataManager Interface](ichanneldatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

