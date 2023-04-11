---
title: ItemOutOfStockException Constructor (IEnumerable(Guid)) (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: ItemOutOfStockException Constructor (IEnumerable(Guid))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.ItemOutOfStockException.#ctor(System.Collections.Generic.IEnumerable{System.Guid})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.itemoutofstockexception.itemoutofstockexception(v=AX.60)
ms:contentKeyID: 49826734
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# ItemOutOfStockException Constructor (IEnumerable(Guid))


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [ItemOutOfStockException](itemoutofstockexception-class-microsoft-dynamics-commerce-runtime.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    rejectedReservationIds As IEnumerable(Of Guid) _
)
'Usage
Dim rejectedReservationIds As IEnumerable(Of Guid)

Dim instance As New ItemOutOfStockException(rejectedReservationIds)
```

``` csharp
public ItemOutOfStockException(
    IEnumerable<Guid> rejectedReservationIds
)
```

``` c++
public:
ItemOutOfStockException(
    IEnumerable<Guid>^ rejectedReservationIds
)
```

#### Parameters

  - rejectedReservationIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[Guid](https://technet.microsoft.com/library/cey1zx63\(v=ax.60\))\>  

## See Also

#### Reference

[ItemOutOfStockException Class](itemoutofstockexception-class-microsoft-dynamics-commerce-runtime.md)

[ItemOutOfStockException Overload](itemoutofstockexception-constructor-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

