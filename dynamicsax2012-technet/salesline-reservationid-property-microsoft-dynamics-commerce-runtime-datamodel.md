---
title: SalesLine.ReservationId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ReservationId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.ReservationId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salesline.reservationid(v=AX.60)
ms:contentKeyID: 49856758
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.ReservationId
dev_langs:
- CSharp
- C++
- VB
---

# ReservationId Property

Gets or sets the reservation identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("RESERVATIONID")> _
<DataMemberAttribute> _
Public Property ReservationId As Guid
    Get
    Set
'Usage
Dim instance As SalesLine
Dim value As Guid

value = instance.ReservationId

instance.ReservationId = value
```

``` csharp
[ColumnAttribute("RESERVATIONID")]
[DataMemberAttribute]
public Guid ReservationId { get; set; }
```

``` c++
[ColumnAttribute(L"RESERVATIONID")]
[DataMemberAttribute]
public:
property Guid ReservationId {
    Guid get ();
    void set (Guid value);
}
```

#### Property Value

Type: [System.Guid](https://technet.microsoft.com/library/cey1zx63\(v=ax.60\))  
Returns [Guid](https://technet.microsoft.com/library/cey1zx63\(v=ax.60\)).  

## See Also

#### Reference

[SalesLine Class](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

