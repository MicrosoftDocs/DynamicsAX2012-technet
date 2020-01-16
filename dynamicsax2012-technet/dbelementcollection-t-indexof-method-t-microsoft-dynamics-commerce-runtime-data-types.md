---
title: DbElementCollection(T).IndexOf Method (T) (Microsoft.Dynamics.Commerce.Runtime.Data.Types)
TOCTitle: IndexOf Method (T)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.Types.DbElementCollection`1.IndexOf(`0)
ms:mtpsurl: https://technet.microsoft.com/library/Dn988499(v=AX.60)
ms:contentKeyID: 65318052
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# IndexOf Method (T)

Returns the index of an element.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data.Types](microsoft-dynamics-commerce-runtime-data-types-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Function IndexOf ( _
    item As T _
) As Integer
'Usage
Dim instance As DbElementCollection
Dim item As T
Dim returnValue As Integer

returnValue = instance.IndexOf(item)
```

``` csharp
public int IndexOf(
    T item
)
```

``` c++
public:
virtual int IndexOf(
    T item
) sealed
```

#### Parameters

  - item  
    Type: [T](dbelementcollection-t-class-microsoft-dynamics-commerce-runtime-data-types.md)  

#### Return Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
The index of element.  

#### Implements

[IList\<T\>.IndexOf(T)](https://technet.microsoft.com/library/3w0148af\(v=ax.60\))  

## See Also

#### Reference

[DbElementCollection\<T\> Class](dbelementcollection-t-class-microsoft-dynamics-commerce-runtime-data-types.md)

[IndexOf Overload](dbelementcollection-t-indexof-method-microsoft-dynamics-commerce-runtime-data-types.md)

[Microsoft.Dynamics.Commerce.Runtime.Data.Types Namespace](microsoft-dynamics-commerce-runtime-data-types-namespace.md)

