---
title: ReserveItemsDataRequest.ItemReservations Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: ItemReservations Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.ReserveItemsDataRequest.ItemReservations
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.dataservices.messages.reserveitemsdatarequest.itemreservations(v=AX.60)
ms:contentKeyID: 65320261
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.ReserveItemsDataRequest.ItemReservations
dev_langs:
- CSharp
- C++
- VB
---

# ItemReservations Property

Gets the collection of item reservations.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ItemReservations As IEnumerable(Of ItemReservation)
    Get
    Private Set
'Usage
Dim instance As ReserveItemsDataRequest
Dim value As IEnumerable(Of ItemReservation)

value = instance.ItemReservations
```

``` csharp
[DataMemberAttribute]
public IEnumerable<ItemReservation> ItemReservations { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property IEnumerable<ItemReservation^>^ ItemReservations {
    IEnumerable<ItemReservation^>^ get ();
    private: void set (IEnumerable<ItemReservation^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[ItemReservation](itemreservation-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [IEnumerable\<T\>](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[ReserveItemsDataRequest Class](reserveitemsdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

