---
title: QuantityDiscountLevel.MinimumQuantity Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: MinimumQuantity Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.QuantityDiscountLevel.MinimumQuantity
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.quantitydiscountlevel.minimumquantity(v=AX.60)
ms:contentKeyID: 49854024
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.QuantityDiscountLevel.MinimumQuantity
dev_langs:
- CSharp
- C++
- VB
---

# MinimumQuantity Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the minimum quantity at which this discount applies.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("QTYLOWEST")> _
<DataMemberAttribute> _
Public Property MinimumQuantity As Decimal
    Get
    Set
'Usage
Dim instance As QuantityDiscountLevel
Dim value As Decimal

value = instance.MinimumQuantity

instance.MinimumQuantity = value
```

``` csharp
[ColumnAttribute("QTYLOWEST")]
[DataMemberAttribute]
public decimal MinimumQuantity { get; set; }
```

``` c++
[ColumnAttribute(L"QTYLOWEST")]
[DataMemberAttribute]
public:
property Decimal MinimumQuantity {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[QuantityDiscountLevel Class](quantitydiscountlevel-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

