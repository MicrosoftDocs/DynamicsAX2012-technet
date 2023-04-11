---
title: IChannelDataManager.GetDescendantCategories Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetDescendantCategories Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.IChannelDataManager.GetDescendantCategories(System.Int64,System.Int64,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.ichanneldatamanager.getdescendantcategories(v=AX.60)
ms:contentKeyID: 65318862
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.IChannelDataManager.GetDescendantCategories
dev_langs:
- CSharp
- C++
- VB
---

# GetDescendantCategories Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Function GetDescendantCategories ( _
    channelId As Long, _
    parentCategoryId As Long, _
    settings As QueryResultSettings _
) As ReadOnlyCollection(Of Category)
'Usage
Dim instance As IChannelDataManager
Dim channelId As Long
Dim parentCategoryId As Long
Dim settings As QueryResultSettings
Dim returnValue As ReadOnlyCollection(Of Category)

returnValue = instance.GetDescendantCategories(channelId, _
    parentCategoryId, settings)
```

``` csharp
ReadOnlyCollection<Category> GetDescendantCategories(
    long channelId,
    long parentCategoryId,
    QueryResultSettings settings
)
```

``` c++
ReadOnlyCollection<Category^>^ GetDescendantCategories(
    long long channelId, 
    long long parentCategoryId, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - channelId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - parentCategoryId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[Category](category-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[IChannelDataManager Interface](ichanneldatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

