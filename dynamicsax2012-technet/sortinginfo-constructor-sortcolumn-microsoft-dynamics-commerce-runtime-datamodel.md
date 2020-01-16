---
title: SortingInfo Constructor (SortColumn ) (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SortingInfo Constructor (SortColumn )
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.SortingInfo.#ctor(Microsoft.Dynamics.Commerce.Runtime.DataModel.SortColumn[])
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.sortinginfo.sortinginfo(v=AX.60)
ms:contentKeyID: 65316726
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# SortingInfo Constructor (SortColumn[])

Initializes a new instance of the [SortingInfo](sortinginfo-class-microsoft-dynamics-commerce-runtime-datamodel.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    ParamArray columns As SortColumn() _
)
'Usage
Dim columns As SortColumn()

Dim instance As New SortingInfo(columns)
```

``` csharp
public SortingInfo(
    params SortColumn[] columns
)
```

``` c++
public:
SortingInfo(
    ... array<SortColumn^>^ columns
)
```

#### Parameters

  - columns  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SortColumn](sortcolumn-class-microsoft-dynamics-commerce-runtime-datamodel.md)\[\]  

## See Also

#### Reference

[SortingInfo Class](sortinginfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[SortingInfo Overload](sortinginfo-constructor-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

