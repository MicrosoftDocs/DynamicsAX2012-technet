---
title: SortingInfo.Add Method  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Add Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.SortingInfo.Add(Microsoft.Dynamics.Commerce.Runtime.DataModel.SortColumn[])
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.sortinginfo.add(v=AX.60)
ms:contentKeyID: 65320571
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SortingInfo.Add
dev_langs:
- CSharp
- C++
- VB
---

# Add Method

Adds the specified columns to order by.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Sub Add ( _
    ParamArray columns As SortColumn() _
)
'Usage
Dim instance As SortingInfo
Dim columns As SortColumn()

instance.Add(columns)
```

``` csharp
public void Add(
    params SortColumn[] columns
)
```

``` c++
public:
void Add(
    ... array<SortColumn^>^ columns
)
```

#### Parameters

  - columns  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SortColumn](sortcolumn-class-microsoft-dynamics-commerce-runtime-datamodel.md)\[\]  

## Remarks

The columns are added in the order they are specified.

## See Also

#### Reference

[SortingInfo Class](sortinginfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

