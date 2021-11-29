---
title: ChannelManager.GetChannelCategoryHierarchy Method (Int64, QueryResultSettings) (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetChannelCategoryHierarchy Method (Int64, QueryResultSettings)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.ChannelManager.GetChannelCategoryHierarchy(System.Int64,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.channelmanager.getchannelcategoryhierarchy(v=AX.60)
ms:contentKeyID: 65319034
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetChannelCategoryHierarchy Method (Int64, QueryResultSettings)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetChannelCategoryHierarchy ( _
    channelId As Long, _
    settings As QueryResultSettings _
) As PagedResult(Of Category)
'Usage
Dim instance As ChannelManager
Dim channelId As Long
Dim settings As QueryResultSettings
Dim returnValue As PagedResult(Of Category)

returnValue = instance.GetChannelCategoryHierarchy(channelId, _
    settings)
```

``` csharp
public PagedResult<Category> GetChannelCategoryHierarchy(
    long channelId,
    QueryResultSettings settings
)
```

``` c++
public:
PagedResult<Category^>^ GetChannelCategoryHierarchy(
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

Type: [Microsoft.Dynamics.Commerce.Runtime.PagedResult](pagedresult-tentity-class-microsoft-dynamics-commerce-runtime.md)\<[Category](category-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ChannelManager Class](channelmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[GetChannelCategoryHierarchy Overload](channelmanager-getchannelcategoryhierarchy-method-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

