---
title: DbElementCollection(T).CopyTo Method (Array, Int32) (Microsoft.Dynamics.Commerce.Runtime.Data.Types)
TOCTitle: CopyTo Method (Array, Int32)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.Types.DbElementCollection`1.CopyTo(System.Array,System.Int32)
ms:mtpsurl: https://technet.microsoft.com/library/Dn969366(v=AX.60)
ms:contentKeyID: 65322979
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# CopyTo Method (Array, Int32)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Copies the entire collection to a compatible one-dimensional array, starting at the beginning of the target array.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data.Types](microsoft-dynamics-commerce-runtime-data-types-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Sub CopyTo ( _
    array As Array, _
    index As Integer _
)
'Usage
Dim instance As DbElementCollection
Dim array As Array
Dim index As Integer

instance.CopyTo(array, index)
```

``` csharp
public void CopyTo(
    Array array,
    int index
)
```

``` c++
public:
virtual void CopyTo(
    Array^ array, 
    int index
) sealed
```

#### Parameters

  - array  
    Type: [System.Array](https://technet.microsoft.com/library/czz5hkty\(v=ax.60\))  

<!-- end list -->

  - index  
    Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

#### Implements

[ICollection.CopyTo(Array, Int32)](https://technet.microsoft.com/library/t4kx53hz\(v=ax.60\))  

## See Also

#### Reference

[DbElementCollection\<T\> Class](dbelementcollection-t-class-microsoft-dynamics-commerce-runtime-data-types.md)

[CopyTo Overload](dbelementcollection-t-copyto-method-microsoft-dynamics-commerce-runtime-data-types.md)

[Microsoft.Dynamics.Commerce.Runtime.Data.Types Namespace](microsoft-dynamics-commerce-runtime-data-types-namespace.md)

