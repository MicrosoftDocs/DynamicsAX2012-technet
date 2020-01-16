---
title: JoinableTableType.JoinColumn Property  (Microsoft.Dynamics.Commerce.Runtime.Data.Types)
TOCTitle: JoinColumn Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.Types.JoinableTableType.JoinColumn
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.types.joinabletabletype.joincolumn(v=AX.60)
ms:contentKeyID: 65321207
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.Types.JoinableTableType.JoinColumn
dev_langs:
- CSharp
- C++
- VB
---

# JoinColumn Property

Gets or sets the join column name of the underlying base table.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data.Types](microsoft-dynamics-commerce-runtime-data-types-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Data (in Microsoft.Dynamics.Commerce.Runtime.Data.dll)

## Syntax

``` vb
'Declaration
Public Property JoinColumn As String
    Get
    Set
'Usage
Dim instance As JoinableTableType
Dim value As String

value = instance.JoinColumn

instance.JoinColumn = value
```

``` csharp
public string JoinColumn { get; set; }
```

``` c++
public:
property String^ JoinColumn {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[JoinableTableType Class](joinabletabletype-class-microsoft-dynamics-commerce-runtime-data-types.md)

[Microsoft.Dynamics.Commerce.Runtime.Data.Types Namespace](microsoft-dynamics-commerce-runtime-data-types-namespace.md)

