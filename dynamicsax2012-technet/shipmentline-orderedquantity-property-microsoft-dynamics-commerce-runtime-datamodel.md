---
title: ShipmentLine.OrderedQuantity Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: OrderedQuantity Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ShipmentLine.OrderedQuantity
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.shipmentline.orderedquantity(v=AX.60)
ms:contentKeyID: 49845037
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ShipmentLine.OrderedQuantity
dev_langs:
- CSharp
- C++
- VB
---

# OrderedQuantity Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the quantity that was originally ordered.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("ORDERED")> _
Public Property OrderedQuantity As Decimal
    Get
    Set
'Usage
Dim instance As ShipmentLine
Dim value As Decimal

value = instance.OrderedQuantity

instance.OrderedQuantity = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("ORDERED")]
public decimal OrderedQuantity { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"ORDERED")]
public:
property Decimal OrderedQuantity {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
The ordered quantity.  

## See Also

#### Reference

[ShipmentLine Class](shipmentline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

