---
title: DbElementCollection(T).Insert Method  (Microsoft.Dynamics.Commerce.Runtime.Data.Types)
TOCTitle: Insert Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.Types.DbElementCollection`1.Insert(System.Int32,`0)
ms:mtpsurl: https://technet.microsoft.com/library/Dn989474(v=AX.60)
ms:contentKeyID: 65319934
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.Types.DbElementCollection`1.Insert
dev_langs:
- CSharp
- C++
- VB
---

# Insert Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Inserts an element in a specific position.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data.Types](microsoft-dynamics-commerce-runtime-data-types-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Sub Insert ( _
    index As Integer, _
    item As T _
)
'Usage
Dim instance As DbElementCollection
Dim index As Integer
Dim item As T

instance.Insert(index, item)
```

``` csharp
public void Insert(
    int index,
    T item
)
```

``` c++
public:
virtual void Insert(
    int index, 
    T item
) sealed
```

#### Parameters

  - index  
    Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

<!-- end list -->

  - item  
    Type: [T](dbelementcollection-t-class-microsoft-dynamics-commerce-runtime-data-types.md)  

#### Implements

[IList\<T\>.Insert(Int32, T)](https://technet.microsoft.com/library/8zsfbxz8\(v=ax.60\))  

## See Also

#### Reference

[DbElementCollection\<T\> Class](dbelementcollection-t-class-microsoft-dynamics-commerce-runtime-data-types.md)

[Microsoft.Dynamics.Commerce.Runtime.Data.Types Namespace](microsoft-dynamics-commerce-runtime-data-types-namespace.md)

