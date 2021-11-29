---
title: ItemIdNotFoundInInventoryNotification Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ItemIdNotFoundInInventoryNotification Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemIdNotFoundInInventoryNotification.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemReservation})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.itemidnotfoundininventorynotification.itemidnotfoundininventorynotification(v=AX.60)
ms:contentKeyID: 65322544
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemIdNotFoundInInventoryNotification.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# ItemIdNotFoundInInventoryNotification Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [ItemIdNotFoundInInventoryNotification](itemidnotfoundininventorynotification-class-microsoft-dynamics-commerce-runtime-datamodel.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    itemReservations As IEnumerable(Of ItemReservation) _
)
'Usage
Dim itemReservations As IEnumerable(Of ItemReservation)

Dim instance As New ItemIdNotFoundInInventoryNotification(itemReservations)
```

``` csharp
public ItemIdNotFoundInInventoryNotification(
    IEnumerable<ItemReservation> itemReservations
)
```

``` c++
public:
ItemIdNotFoundInInventoryNotification(
    IEnumerable<ItemReservation^>^ itemReservations
)
```

#### Parameters

  - itemReservations  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ItemReservation](itemreservation-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ItemIdNotFoundInInventoryNotification Class](itemidnotfoundininventorynotification-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

