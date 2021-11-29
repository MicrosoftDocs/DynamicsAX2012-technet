---
title: DefaultSortOrderAttribute.ColumnName Property  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: ColumnName Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DefaultSortOrderAttribute.ColumnName
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.defaultsortorderattribute.columnname(v=AX.60)
ms:contentKeyID: 62210440
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DefaultSortOrderAttribute.ColumnName
dev_langs:
- CSharp
- C++
- VB
---

# ColumnName Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the column name to be sorted.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Property ColumnName As String
    Get
    Set
'Usage
Dim instance As DefaultSortOrderAttribute
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

[DefaultSortOrderAttribute Class](defaultsortorderattribute-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

