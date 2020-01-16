---
title: DataColumn.ColumnName Property  (Microsoft.Dynamics.Commerce.Runtime.Data.Types)
TOCTitle: ColumnName Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataColumn.ColumnName
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.types.datacolumn.columnname(v=AX.60)
ms:contentKeyID: 65319049
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataColumn.ColumnName
dev_langs:
- CSharp
- C++
- VB
---

# ColumnName Property

Gets or sets the column name.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data.Types](microsoft-dynamics-commerce-runtime-data-types-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Property ColumnName As String
    Get
    Set
'Usage
Dim instance As DataColumn
Dim value As String

value = instance.ColumnName

instance.ColumnName = value
```

``` csharp
public string ColumnName { get; set; }
```

``` c++
public:
property String^ ColumnName {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[DataColumn Class](datacolumn-class-microsoft-dynamics-commerce-runtime-data-types.md)

[Microsoft.Dynamics.Commerce.Runtime.Data.Types Namespace](microsoft-dynamics-commerce-runtime-data-types-namespace.md)

