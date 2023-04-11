---
title: QuantityDiscountLevel.DiscountPriceOrPercent Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DiscountPriceOrPercent Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.QuantityDiscountLevel.DiscountPriceOrPercent
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.quantitydiscountlevel.discountpriceorpercent(v=AX.60)
ms:contentKeyID: 49853753
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.QuantityDiscountLevel.DiscountPriceOrPercent
dev_langs:
- CSharp
- C++
- VB
---

# DiscountPriceOrPercent Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the discount amount for the given quantity.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("PRICEDISCPCT")> _
<DataMemberAttribute> _
Public Property DiscountPriceOrPercent As Decimal
    Get
    Set
'Usage
Dim instance As QuantityDiscountLevel
Dim value As Decimal

value = instance.DiscountPriceOrPercent

instance.DiscountPriceOrPercent = value
```

``` csharp
[ColumnAttribute("PRICEDISCPCT")]
[DataMemberAttribute]
public decimal DiscountPriceOrPercent { get; set; }
```

``` c++
[ColumnAttribute(L"PRICEDISCPCT")]
[DataMemberAttribute]
public:
property Decimal DiscountPriceOrPercent {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## Remarks

This can be either a unit price or percent off amount, based on the discount type set on the quantity discount header configuration.

## See Also

#### Reference

[QuantityDiscountLevel Class](quantitydiscountlevel-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

