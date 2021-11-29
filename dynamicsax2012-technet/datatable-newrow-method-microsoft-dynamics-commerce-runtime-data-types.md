---
title: DataTable.NewRow Method  (Microsoft.Dynamics.Commerce.Runtime.Data.Types)
TOCTitle: NewRow Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataTable.NewRow
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.types.datatable.newrow(v=AX.60)
ms:contentKeyID: 65322305
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataTable.NewRow
dev_langs:
- CSharp
- C++
- VB
---

# NewRow Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Creates a new data row based on this table's column schema.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data.Types](microsoft-dynamics-commerce-runtime-data-types-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Function NewRow As DataRow
'Usage
Dim instance As DataTable
Dim returnValue As DataRow

returnValue = instance.NewRow()
```

``` csharp
public DataRow NewRow()
```

``` c++
public:
DataRow^ NewRow()
```

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataRow](datarow-class-microsoft-dynamics-commerce-runtime-data-types.md)  
Returns a new data row.  

## See Also

#### Reference

[DataTable Class](datatable-class-microsoft-dynamics-commerce-runtime-data-types.md)

[Microsoft.Dynamics.Commerce.Runtime.Data.Types Namespace](microsoft-dynamics-commerce-runtime-data-types-namespace.md)

