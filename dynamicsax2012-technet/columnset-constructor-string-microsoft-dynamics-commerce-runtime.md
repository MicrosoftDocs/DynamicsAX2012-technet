---
title: ColumnSet Constructor (String ) (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: ColumnSet Constructor (String )
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.ColumnSet.#ctor(System.String[])
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.columnset.columnset(v=AX.60)
ms:contentKeyID: 49852617
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# ColumnSet Constructor (String[])

Initializes a new instance of the [ColumnSet](columnset-class-microsoft-dynamics-commerce-runtime.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    ParamArray columns As String() _
)
'Usage
Dim columns As String()

Dim instance As New ColumnSet(columns)
```

``` csharp
public ColumnSet(
    params string[] columns
)
```

``` c++
public:
ColumnSet(
    ... array<String^>^ columns
)
```

#### Parameters

  - columns  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))\[\]  

## See Also

#### Reference

[ColumnSet Class](columnset-class-microsoft-dynamics-commerce-runtime.md)

[ColumnSet Overload](columnset-constructor-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

