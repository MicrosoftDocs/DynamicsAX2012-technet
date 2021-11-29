---
title: DbElementCollection(T).Remove Method  (Microsoft.Dynamics.Commerce.Runtime.Data.Types)
TOCTitle: Remove Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.Types.DbElementCollection`1.Remove(`0)
ms:mtpsurl: https://technet.microsoft.com/library/Dn968165(v=AX.60)
ms:contentKeyID: 65320529
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.Types.DbElementCollection`1.Remove
dev_langs:
- CSharp
- C++
- VB
---

# Remove Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Removes an element from the collection.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data.Types](microsoft-dynamics-commerce-runtime-data-types-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Function Remove ( _
    item As T _
) As Boolean
'Usage
Dim instance As DbElementCollection
Dim item As T
Dim returnValue As Boolean

returnValue = instance.Remove(item)
```

``` csharp
public bool Remove(
    T item
)
```

``` c++
public:
virtual bool Remove(
    T item
) sealed
```

#### Parameters

  - item  
    Type: [T](dbelementcollection-t-class-microsoft-dynamics-commerce-runtime-data-types.md)  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Whether the element has been removed or not.  

#### Implements

[ICollection\<T\>.Remove(T)](https://technet.microsoft.com/library/bye7h94w\(v=ax.60\))  

## See Also

#### Reference

[DbElementCollection\<T\> Class](dbelementcollection-t-class-microsoft-dynamics-commerce-runtime-data-types.md)

[Microsoft.Dynamics.Commerce.Runtime.Data.Types Namespace](microsoft-dynamics-commerce-runtime-data-types-namespace.md)

