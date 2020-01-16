---
title: ColumnSet.AllColumns Property  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: AllColumns Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.ColumnSet.AllColumns
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.columnset.allcolumns(v=AX.60)
ms:contentKeyID: 49854455
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.ColumnSet.AllColumns
dev_langs:
- CSharp
- C++
- VB
---

# AllColumns Property

Gets a value indicating whether all columns are to be selected.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public ReadOnly Property AllColumns As Boolean
    Get
'Usage
Dim instance As ColumnSet
Dim value As Boolean

value = instance.AllColumns
```

``` csharp
public bool AllColumns { get; }
```

``` c++
public:
property bool AllColumns {
    bool get ();
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
If true all columns are to be selected; otherwise, false.  

## See Also

#### Reference

[ColumnSet Class](columnset-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

