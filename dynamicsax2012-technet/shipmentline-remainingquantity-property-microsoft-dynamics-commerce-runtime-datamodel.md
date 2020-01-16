---
title: ShipmentLine.RemainingQuantity Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: RemainingQuantity Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ShipmentLine.RemainingQuantity
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.shipmentline.remainingquantity(v=AX.60)
ms:contentKeyID: 49855613
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ShipmentLine.RemainingQuantity
dev_langs:
- CSharp
- C++
- VB
---

# RemainingQuantity Property

Gets or sets the quantity that still needs to be packed and shipped.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("REMAIN")> _
Public Property RemainingQuantity As Decimal
    Get
    Set
'Usage
Dim instance As ShipmentLine
Dim value As Decimal

value = instance.RemainingQuantity

instance.RemainingQuantity = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("REMAIN")]
public decimal RemainingQuantity { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"REMAIN")]
public:
property Decimal RemainingQuantity {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
The remaining quantity.  

## See Also

#### Reference

[ShipmentLine Class](shipmentline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

