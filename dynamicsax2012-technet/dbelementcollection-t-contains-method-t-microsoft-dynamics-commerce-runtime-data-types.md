---
title: DbElementCollection(T).Contains Method (T) (Microsoft.Dynamics.Commerce.Runtime.Data.Types)
TOCTitle: Contains Method (T)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.Types.DbElementCollection`1.Contains(`0)
ms:mtpsurl: https://technet.microsoft.com/library/Dn966508(v=AX.60)
ms:contentKeyID: 65316456
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# Contains Method (T)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Returns whether an element is contained in the collection.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data.Types](microsoft-dynamics-commerce-runtime-data-types-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Function Contains ( _
    item As T _
) As Boolean
'Usage
Dim instance As DbElementCollection
Dim item As T
Dim returnValue As Boolean

returnValue = instance.Contains(item)
```

``` csharp
public bool Contains(
    T item
)
```

``` c++
public:
virtual bool Contains(
    T item
) sealed
```

#### Parameters

  - item  
    Type: [T](dbelementcollection-t-class-microsoft-dynamics-commerce-runtime-data-types.md)  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Whether the element is contained in the collection.  

#### Implements

[ICollection\<T\>.Contains(T)](https://technet.microsoft.com/library/k5cf1d56\(v=ax.60\))  

## See Also

#### Reference

[DbElementCollection\<T\> Class](dbelementcollection-t-class-microsoft-dynamics-commerce-runtime-data-types.md)

[Contains Overload](dbelementcollection-t-contains-method-microsoft-dynamics-commerce-runtime-data-types.md)

[Microsoft.Dynamics.Commerce.Runtime.Data.Types Namespace](microsoft-dynamics-commerce-runtime-data-types-namespace.md)

