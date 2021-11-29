---
title: ShipmentLine.DeliveredQuantity Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DeliveredQuantity Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ShipmentLine.DeliveredQuantity
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.shipmentline.deliveredquantity(v=AX.60)
ms:contentKeyID: 49824793
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ShipmentLine.DeliveredQuantity
dev_langs:
- CSharp
- C++
- VB
---

# DeliveredQuantity Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the quantity that has been delivered.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("QTY")> _
Public Property DeliveredQuantity As Decimal
    Get
    Set
'Usage
Dim instance As ShipmentLine
Dim value As Decimal

value = instance.DeliveredQuantity

instance.DeliveredQuantity = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("QTY")]
public decimal DeliveredQuantity { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"QTY")]
public:
property Decimal DeliveredQuantity {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
The delivered quantity.  

## See Also

#### Reference

[ShipmentLine Class](shipmentline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

