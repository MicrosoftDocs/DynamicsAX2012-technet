---
title: DbElementCollection(T).CopyTo Method (T , Int32) (Microsoft.Dynamics.Commerce.Runtime.Data.Types)
TOCTitle: CopyTo Method (T , Int32)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.Types.DbElementCollection`1.CopyTo(`0[],System.Int32)
ms:mtpsurl: https://technet.microsoft.com/library/Dn989118(v=AX.60)
ms:contentKeyID: 65319073
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# CopyTo Method (T[], Int32)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Copies the entire collection to a compatible one-dimensional array, starting at the beginning of the target array.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data.Types](microsoft-dynamics-commerce-runtime-data-types-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Sub CopyTo ( _
    array As T(), _
    arrayIndex As Integer _
)
'Usage
Dim instance As DbElementCollection
Dim array As T()
Dim arrayIndex As Integer

instance.CopyTo(array, arrayIndex)
```

``` csharp
public void CopyTo(
    T[] array,
    int arrayIndex
)
```

``` c++
public:
virtual void CopyTo(
    array<T>^ array, 
    int arrayIndex
) sealed
```

#### Parameters

  - array  
    Type: [T](dbelementcollection-t-class-microsoft-dynamics-commerce-runtime-data-types.md)\[\]  

<!-- end list -->

  - arrayIndex  
    Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

#### Implements

[ICollection\<T\>.CopyTo(T\[\], Int32)](https://technet.microsoft.com/library/0efx51xw\(v=ax.60\))  

## See Also

#### Reference

[DbElementCollection\<T\> Class](dbelementcollection-t-class-microsoft-dynamics-commerce-runtime-data-types.md)

[CopyTo Overload](dbelementcollection-t-copyto-method-microsoft-dynamics-commerce-runtime-data-types.md)

[Microsoft.Dynamics.Commerce.Runtime.Data.Types Namespace](microsoft-dynamics-commerce-runtime-data-types-namespace.md)

