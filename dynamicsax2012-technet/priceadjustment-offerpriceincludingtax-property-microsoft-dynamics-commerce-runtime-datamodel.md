---
title: PriceAdjustment.OfferPriceIncludingTax Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: OfferPriceIncludingTax Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceAdjustment.OfferPriceIncludingTax
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.priceadjustment.offerpriceincludingtax(v=AX.60)
ms:contentKeyID: 49846390
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceAdjustment.OfferPriceIncludingTax
dev_langs:
- CSharp
- C++
- VB
---

# OfferPriceIncludingTax Property

Gets the final adjusted price including tax for "Price including tax" method.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("OFFERPRICEINCLTAX")> _
<DataMemberAttribute> _
Public Property OfferPriceIncludingTax As Decimal
    Get
    Friend Set
'Usage
Dim instance As PriceAdjustment
Dim value As Decimal

value = instance.OfferPriceIncludingTax
```

``` csharp
[ColumnAttribute("OFFERPRICEINCLTAX")]
[DataMemberAttribute]
public decimal OfferPriceIncludingTax { get; internal set; }
```

``` c++
[ColumnAttribute(L"OFFERPRICEINCLTAX")]
[DataMemberAttribute]
public:
property Decimal OfferPriceIncludingTax {
    Decimal get ();
    internal: void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[PriceAdjustment Class](priceadjustment-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

