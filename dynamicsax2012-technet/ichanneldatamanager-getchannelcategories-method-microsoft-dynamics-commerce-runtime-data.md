---
title: IChannelDataManager.GetChannelCategories Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetChannelCategories Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.IChannelDataManager.GetChannelCategories(System.Int64,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.ichanneldatamanager.getchannelcategories(v=AX.60)
ms:contentKeyID: 65321881
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.IChannelDataManager.GetChannelCategories
dev_langs:
- CSharp
- C++
- VB
---

# GetChannelCategories Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Function GetChannelCategories ( _
    channelId As Long, _
    settings As QueryResultSettings _
) As ReadOnlyCollection(Of Category)
'Usage
Dim instance As IChannelDataManager
Dim channelId As Long
Dim settings As QueryResultSettings
Dim returnValue As ReadOnlyCollection(Of Category)

returnValue = instance.GetChannelCategories(channelId, _
    settings)
```

``` csharp
ReadOnlyCollection<Category> GetChannelCategories(
    long channelId,
    QueryResultSettings settings
)
```

``` c++
ReadOnlyCollection<Category^>^ GetChannelCategories(
    long long channelId, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - channelId  
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

