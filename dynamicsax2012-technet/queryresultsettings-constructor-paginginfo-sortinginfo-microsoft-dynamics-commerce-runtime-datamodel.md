---
title: QueryResultSettings Constructor (PagingInfo, SortingInfo) (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: QueryResultSettings Constructor (PagingInfo, SortingInfo)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings.#ctor(Microsoft.Dynamics.Commerce.Runtime.DataModel.PagingInfo,Microsoft.Dynamics.Commerce.Runtime.DataModel.SortingInfo)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.queryresultsettings.queryresultsettings(v=AX.60)
ms:contentKeyID: 65321473
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# QueryResultSettings Constructor (PagingInfo, SortingInfo)

Initializes a new instance of the [QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    paging As PagingInfo, _
    sorting As SortingInfo _
)
'Usage
Dim paging As PagingInfo
Dim sorting As SortingInfo

Dim instance As New QueryResultSettings(paging, _
    sorting)
```

``` csharp
public QueryResultSettings(
    PagingInfo paging,
    SortingInfo sorting
)
```

``` c++
public:
QueryResultSettings(
    PagingInfo^ paging, 
    SortingInfo^ sorting
)
```

#### Parameters

  - paging  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.PagingInfo](paginginfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - sorting  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SortingInfo](sortinginfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[QueryResultSettings Class](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[QueryResultSettings Overload](queryresultsettings-constructor-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

