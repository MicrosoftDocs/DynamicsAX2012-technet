﻿---
title: QueryResultSettings Constructor (ColumnSet, PagingInfo) (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: QueryResultSettings Constructor (ColumnSet, PagingInfo)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings.#ctor(Microsoft.Dynamics.Commerce.Runtime.ColumnSet,Microsoft.Dynamics.Commerce.Runtime.DataModel.PagingInfo)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.queryresultsettings.queryresultsettings(v=AX.60)
ms:contentKeyID: 65321411
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# QueryResultSettings Constructor (ColumnSet, PagingInfo)

Initializes a new instance of the [QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    columnSet As ColumnSet, _
    paging As PagingInfo _
)
'Usage
Dim columnSet As ColumnSet
Dim paging As PagingInfo

Dim instance As New QueryResultSettings(columnSet, _
    paging)
```

``` csharp
public QueryResultSettings(
    ColumnSet columnSet,
    PagingInfo paging
)
```

``` c++
public:
QueryResultSettings(
    ColumnSet^ columnSet, 
    PagingInfo^ paging
)
```

#### Parameters

  - columnSet  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ColumnSet](columnset-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - paging  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.PagingInfo](paginginfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[QueryResultSettings Class](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[QueryResultSettings Overload](queryresultsettings-constructor-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)
