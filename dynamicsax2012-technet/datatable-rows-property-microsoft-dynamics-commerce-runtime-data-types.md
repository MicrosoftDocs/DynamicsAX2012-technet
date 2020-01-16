---
title: DataTable.Rows Property  (Microsoft.Dynamics.Commerce.Runtime.Data.Types)
TOCTitle: Rows Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataTable.Rows
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.types.datatable.rows(v=AX.60)
ms:contentKeyID: 65316214
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataTable.Rows
dev_langs:
- CSharp
- C++
- VB
---

# Rows Property

Gets the collection of rows for this table.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data.Types](microsoft-dynamics-commerce-runtime-data-types-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Property Rows As DataRowCollection
    Get
    Private Set
'Usage
Dim instance As DataTable
Dim value As DataRowCollection

value = instance.Rows
```

``` csharp
public DataRowCollection Rows { get; private set; }
```

``` c++
public:
property DataRowCollection^ Rows {
    DataRowCollection^ get ();
    private: void set (DataRowCollection^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataRowCollection](datarowcollection-class-microsoft-dynamics-commerce-runtime-data-types.md)  
Returns [DataRowCollection](datarowcollection-class-microsoft-dynamics-commerce-runtime-data-types.md).  

## See Also

#### Reference

[DataTable Class](datatable-class-microsoft-dynamics-commerce-runtime-data-types.md)

[Microsoft.Dynamics.Commerce.Runtime.Data.Types Namespace](microsoft-dynamics-commerce-runtime-data-types-namespace.md)

