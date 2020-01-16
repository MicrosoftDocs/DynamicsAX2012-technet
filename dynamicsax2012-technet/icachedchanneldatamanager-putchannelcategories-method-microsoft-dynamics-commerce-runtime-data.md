---
title: ICachedChannelDataManager.PutChannelCategories Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: PutChannelCategories Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ICachedChannelDataManager.PutChannelCategories(System.Int64,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings,System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.Category})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.icachedchanneldatamanager.putchannelcategories(v=AX.60)
ms:contentKeyID: 65322341
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ICachedChannelDataManager.PutChannelCategories
dev_langs:
- CSharp
- C++
- VB
---

# PutChannelCategories Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Sub PutChannelCategories ( _
    channelId As Long, _
    settings As QueryResultSettings, _
    result As ReadOnlyCollection(Of Category) _
)
'Usage
Dim instance As ICachedChannelDataManager
Dim channelId As Long
Dim settings As QueryResultSettings
Dim result As ReadOnlyCollection(Of Category)

instance.PutChannelCategories(channelId, _
    settings, result)
```

``` csharp
void PutChannelCategories(
    long channelId,
    QueryResultSettings settings,
    ReadOnlyCollection<Category> result
)
```

``` c++
void PutChannelCategories(
    long long channelId, 
    QueryResultSettings^ settings, 
    ReadOnlyCollection<Category^>^ result
)
```

#### Parameters

  - channelId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - result  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[Category](category-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ICachedChannelDataManager Interface](icachedchanneldatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

