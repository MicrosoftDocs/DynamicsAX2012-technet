---
title: ItemReservation.ReservationId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ReservationId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemReservation.ReservationId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.itemreservation.reservationid(v=AX.60)
ms:contentKeyID: 49846679
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemReservation.ReservationId
dev_langs:
- CSharp
- C++
- VB
---

# ReservationId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the reservation identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("RESERVATIONID")> _
Public Property ReservationId As Guid
    Get
    Set
'Usage
Dim instance As ItemReservation
Dim value As Guid

value = instance.ReservationId

instance.ReservationId = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("RESERVATIONID")]
public Guid ReservationId { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"RESERVATIONID")]
public:
property Guid ReservationId {
    Guid get ();
    void set (Guid value);
}
```

#### Property Value

Type: [System.Guid](https://technet.microsoft.com/library/cey1zx63\(v=ax.60\))  
The reservation identifier.  

## See Also

#### Reference

[ItemReservation Class](itemreservation-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

