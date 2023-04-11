---
title: ItemOutOfStockException.RejectedReservationIds Property  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: RejectedReservationIds Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.ItemOutOfStockException.RejectedReservationIds
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.itemoutofstockexception.rejectedreservationids(v=AX.60)
ms:contentKeyID: 49821248
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.ItemOutOfStockException.RejectedReservationIds
dev_langs:
- CSharp
- C++
- VB
---

# RejectedReservationIds Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The rejected reservation IDs.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Property RejectedReservationIds As ReadOnlyCollection(Of Guid)
    Get
    Private Set
'Usage
Dim instance As ItemOutOfStockException
Dim value As ReadOnlyCollection(Of Guid)

value = instance.RejectedReservationIds
```

``` csharp
public ReadOnlyCollection<Guid> RejectedReservationIds { get; private set; }
```

``` c++
public:
property ReadOnlyCollection<Guid>^ RejectedReservationIds {
    ReadOnlyCollection<Guid>^ get ();
    private: void set (ReadOnlyCollection<Guid>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[Guid](https://technet.microsoft.com/library/cey1zx63\(v=ax.60\))\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[ItemOutOfStockException Class](itemoutofstockexception-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

