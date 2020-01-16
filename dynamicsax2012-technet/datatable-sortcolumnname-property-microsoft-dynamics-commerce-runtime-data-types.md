---
title: DataTable.SortColumnName Property  (Microsoft.Dynamics.Commerce.Runtime.Data.Types)
TOCTitle: SortColumnName Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataTable.SortColumnName
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.types.datatable.sortcolumnname(v=AX.60)
ms:contentKeyID: 65318476
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataTable.SortColumnName
dev_langs:
- CSharp
- C++
- VB
---

# SortColumnName Property

Gets or sets the sort column name.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data.Types](microsoft-dynamics-commerce-runtime-data-types-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Property SortColumnName As String
    Get
    Set
'Usage
Dim instance As DataTable
Dim value As String

value = instance.SortColumnName

instance.SortColumnName = value
```

``` csharp
public string SortColumnName { get; set; }
```

``` c++
public:
property String^ SortColumnName {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[DataTable Class](datatable-class-microsoft-dynamics-commerce-runtime-data-types.md)

[Microsoft.Dynamics.Commerce.Runtime.Data.Types Namespace](microsoft-dynamics-commerce-runtime-data-types-namespace.md)

