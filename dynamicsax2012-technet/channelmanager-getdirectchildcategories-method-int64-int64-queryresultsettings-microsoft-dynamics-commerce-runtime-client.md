---
title: ChannelManager.GetDirectChildCategories Method (Int64, Int64, QueryResultSettings) (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetDirectChildCategories Method (Int64, Int64, QueryResultSettings)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.ChannelManager.GetDirectChildCategories(System.Int64,System.Int64,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.client.channelmanager.getdirectchildcategories(v=AX.60)
ms:contentKeyID: 65322964
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetDirectChildCategories Method (Int64, Int64, QueryResultSettings)

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetDirectChildCategories ( _
    channelId As Long, _
    parentCategoryId As Long, _
    settings As QueryResultSettings _
) As PagedResult(Of Category)
'Usage
Dim instance As ChannelManager
Dim channelId As Long
Dim parentCategoryId As Long
Dim settings As QueryResultSettings
Dim returnValue As PagedResult(Of Category)

returnValue = instance.GetDirectChildCategories(channelId, _
    parentCategoryId, settings)
```

``` csharp
public PagedResult<Category> GetDirectChildCategories(
    long channelId,
    long parentCategoryId,
    QueryResultSettings settings
)
```

``` c++
public:
PagedResult<Category^>^ GetDirectChildCategories(
    long long channelId, 
    long long parentCategoryId, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - channelId  
    Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - parentCategoryId  
    Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.PagedResult](pagedresult-tentity-class-microsoft-dynamics-commerce-runtime.md)\<[Category](category-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ChannelManager Class](channelmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[GetDirectChildCategories Overload](channelmanager-getdirectchildcategories-method-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

