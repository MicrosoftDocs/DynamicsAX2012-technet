---
title: ICachedChannelDataManager.PutChannelCategoryAttributesByChannelId Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: PutChannelCategoryAttributesByChannelId Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ICachedChannelDataManager.PutChannelCategoryAttributesByChannelId(System.Int64,System.Collections.Generic.IEnumerable{System.Int64},Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings,System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeCategory})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.icachedchanneldatamanager.putchannelcategoryattributesbychannelid(v=AX.60)
ms:contentKeyID: 65317209
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ICachedChannelDataManager.PutChannelCategoryAttributesByChannelId
dev_langs:
- CSharp
- C++
- VB
---

# PutChannelCategoryAttributesByChannelId Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Sub PutChannelCategoryAttributesByChannelId ( _
    channelId As Long, _
    categoryIds As IEnumerable(Of Long), _
    settings As QueryResultSettings, _
    result As ReadOnlyCollection(Of AttributeCategory) _
)
'Usage
Dim instance As ICachedChannelDataManager
Dim channelId As Long
Dim categoryIds As IEnumerable(Of Long)
Dim settings As QueryResultSettings
Dim result As ReadOnlyCollection(Of AttributeCategory)

instance.PutChannelCategoryAttributesByChannelId(channelId, _
    categoryIds, settings, result)
```

``` csharp
void PutChannelCategoryAttributesByChannelId(
    long channelId,
    IEnumerable<long> categoryIds,
    QueryResultSettings settings,
    ReadOnlyCollection<AttributeCategory> result
)
```

``` c++
void PutChannelCategoryAttributesByChannelId(
    long long channelId, 
    IEnumerable<long long>^ categoryIds, 
    QueryResultSettings^ settings, 
    ReadOnlyCollection<AttributeCategory^>^ result
)
```

#### Parameters

  - channelId  
    Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - categoryIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))\>  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - result  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[AttributeCategory](attributecategory-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ICachedChannelDataManager Interface](icachedchanneldatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

