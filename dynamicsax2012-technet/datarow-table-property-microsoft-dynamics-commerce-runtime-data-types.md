---
title: DataRow.Table Property  (Microsoft.Dynamics.Commerce.Runtime.Data.Types)
TOCTitle: Table Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataRow.Table
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.types.datarow.table(v=AX.60)
ms:contentKeyID: 65320574
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataRow.Table
dev_langs:
- CSharp
- C++
- VB
---

# Table Property

Gets the data table that contains this data row.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data.Types](microsoft-dynamics-commerce-runtime-data-types-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Property Table As DataTable
    Get
    Private Set
'Usage
Dim instance As DataRow
Dim value As DataTable

value = instance.Table
```

``` csharp
public DataTable Table { get; private set; }
```

``` c++
public:
property DataTable^ Table {
    DataTable^ get ();
    private: void set (DataTable^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataTable](datatable-class-microsoft-dynamics-commerce-runtime-data-types.md)  
Returns [DataTable](datatable-class-microsoft-dynamics-commerce-runtime-data-types.md).  

## See Also

#### Reference

[DataRow Class](datarow-class-microsoft-dynamics-commerce-runtime-data-types.md)

[Microsoft.Dynamics.Commerce.Runtime.Data.Types Namespace](microsoft-dynamics-commerce-runtime-data-types-namespace.md)

