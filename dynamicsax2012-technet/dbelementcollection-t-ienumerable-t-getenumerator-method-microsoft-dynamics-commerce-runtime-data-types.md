---
title: DbElementCollection(T).IEnumerable(T).GetEnumerator Method  (Microsoft.Dynamics.Commerce.Runtime.Data.Types)
TOCTitle: IEnumerable(T).GetEnumerator Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.Types.DbElementCollection`1.System#Collections#Generic#IEnumerable{T}#GetEnumerator
ms:mtpsurl: https://technet.microsoft.com/library/Dn989492(v=AX.60)
ms:contentKeyID: 65319952
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- IEnumerable.GetEnumerator
- DbElementCollection`1.IEnumerable.GetEnumerator
- Microsoft.Dynamics.Commerce.Runtime.Data.Types.DbElementCollection`1.IEnumerable.GetEnumerator
dev_langs:
- CSharp
- C++
- VB
---

# IEnumerable(T).GetEnumerator Method

Returns an enumerator that iterates through the collection.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data.Types](microsoft-dynamics-commerce-runtime-data-types-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Private Function GetEnumerator As IEnumerator(Of T)
    Implements IEnumerable(Of T).GetEnumerator
'Usage
Dim instance As DbElementCollection
Dim returnValue As IEnumerator(Of T)

returnValue = CType(instance, IEnumerable(Of T)).GetEnumerator()
```

``` csharp
IEnumerator<T> IEnumerable<T>.GetEnumerator()
```

``` c++
private:
virtual IEnumerator<T>^ GetEnumerator() sealed = IEnumerable<T>::GetEnumerator
```

#### Return Value

Type: [System.Collections.Generic.IEnumerator](https://technet.microsoft.com/library/78dfe2yb\(v=ax.60\))\<[T](dbelementcollection-t-class-microsoft-dynamics-commerce-runtime-data-types.md)\>  
An enumerator that iterates through the collection.  

#### Implements

[IEnumerable\<T\>.GetEnumerator()](https://technet.microsoft.com/library/s793z9y2\(v=ax.60\))  

## See Also

#### Reference

[DbElementCollection\<T\> Class](dbelementcollection-t-class-microsoft-dynamics-commerce-runtime-data-types.md)

[Microsoft.Dynamics.Commerce.Runtime.Data.Types Namespace](microsoft-dynamics-commerce-runtime-data-types-namespace.md)

