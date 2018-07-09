---
title: ColumnSet(T) Constructor (T ) (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: ColumnSet(T) Constructor (T )
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.ColumnSet`1.#ctor(`0[])
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn737028(v=AX.60)
ms:contentKeyID: 62201733
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# ColumnSet(T) Constructor (T )[AX 2012]

Initializes a new instance of the [ColumnSet\<T\>](columnset-t-class-microsoft-dynamics-commerce-runtime.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Protected Sub New ( _
    ParamArray columns As T() _
)
'Usage
Dim columns As T()

Dim instance As New ColumnSet(columns)
```

``` csharp
protected ColumnSet(
    params T[] columns
)
```

``` c++
protected:
ColumnSet(
    ... array<T>^ columns
)
```

#### Parameters

  - columns  
    Type: [T](columnset-t-class-microsoft-dynamics-commerce-runtime.md)\[\]  

## See Also

#### Reference

[ColumnSet\<T\> Class](columnset-t-class-microsoft-dynamics-commerce-runtime.md)

[ColumnSet\<T\> Overload](columnset-t-constructor-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

