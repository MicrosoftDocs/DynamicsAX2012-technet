---
title: ColumnSet(T).Columns Property  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: Columns Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.ColumnSet`1.Columns
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn738619(v=AX.60)
ms:contentKeyID: 62208906
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.ColumnSet`1.Columns
dev_langs:
- CSharp
- C++
- VB
---

# Columns Property

Gets the underlying column collection.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Protected ReadOnly Property Columns As IEnumerable(Of T)
    Get
'Usage
Dim value As IEnumerable(Of T)

value = Me.Columns
```

``` csharp
protected IEnumerable<T> Columns { get; }
```

``` c++
protected:
property IEnumerable<T>^ Columns {
    IEnumerable<T>^ get ();
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[T](columnset-t-class-microsoft-dynamics-commerce-runtime.md)\>  
Returns [IEnumerable\<T\>](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[ColumnSet\<T\> Class](columnset-t-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

