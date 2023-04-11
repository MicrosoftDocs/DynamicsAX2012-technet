---
title: TransferOrderLine.QuantityRemainShip Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: QuantityRemainShip Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TransferOrderLine.QuantityRemainShip
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.transferorderline.quantityremainship(v=AX.60)
ms:contentKeyID: 62206735
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TransferOrderLine.QuantityRemainShip
dev_langs:
- CSharp
- C++
- VB
---

# QuantityRemainShip Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the quantity remaining to ship.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("QUANTITYREMAINSHIP")> _
<DataMemberAttribute> _
Public Property QuantityRemainShip As Decimal
    Get
    Set
'Usage
Dim instance As TransferOrderLine
Dim value As Decimal

value = instance.QuantityRemainShip

instance.QuantityRemainShip = value
```

``` csharp
[ColumnAttribute("QUANTITYREMAINSHIP")]
[DataMemberAttribute]
public decimal QuantityRemainShip { get; set; }
```

``` c++
[ColumnAttribute(L"QUANTITYREMAINSHIP")]
[DataMemberAttribute]
public:
property Decimal QuantityRemainShip {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[TransferOrderLine Class](transferorderline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

