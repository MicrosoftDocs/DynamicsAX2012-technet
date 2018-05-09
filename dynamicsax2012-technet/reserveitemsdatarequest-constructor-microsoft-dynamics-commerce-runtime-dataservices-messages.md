---
title: ReserveItemsDataRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: ReserveItemsDataRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.ReserveItemsDataRequest.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemReservation})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.dataservices.messages.reserveitemsdatarequest.reserveitemsdatarequest(v=AX.60)
ms:contentKeyID: 65316401
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.ReserveItemsDataRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# ReserveItemsDataRequest Constructor

Initializes a new instance of the [ReserveItemsDataRequest](reserveitemsdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    itemReservations As IEnumerable(Of ItemReservation) _
)
'Usage
Dim itemReservations As IEnumerable(Of ItemReservation)

Dim instance As New ReserveItemsDataRequest(itemReservations)
```

``` csharp
public ReserveItemsDataRequest(
    IEnumerable<ItemReservation> itemReservations
)
```

``` c++
public:
ReserveItemsDataRequest(
    IEnumerable<ItemReservation^>^ itemReservations
)
```

#### Parameters

  - itemReservations  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[ItemReservation](itemreservation-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ReserveItemsDataRequest Class](reserveitemsdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

