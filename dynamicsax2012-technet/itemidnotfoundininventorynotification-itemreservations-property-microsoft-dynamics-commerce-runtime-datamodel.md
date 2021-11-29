---
title: ItemIdNotFoundInInventoryNotification.ItemReservations Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ItemReservations Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemIdNotFoundInInventoryNotification.ItemReservations
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.itemidnotfoundininventorynotification.itemreservations(v=AX.60)
ms:contentKeyID: 65320321
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemIdNotFoundInInventoryNotification.ItemReservations
dev_langs:
- CSharp
- C++
- VB
---

# ItemReservations Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the collection of item reservations.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ItemReservations As IEnumerable(Of ItemReservation)
    Get
    Private Set
'Usage
Dim instance As ItemIdNotFoundInInventoryNotification
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

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ItemReservation](itemreservation-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [IEnumerable\<T\>](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[ItemIdNotFoundInInventoryNotification Class](itemidnotfoundininventorynotification-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

