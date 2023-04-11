---
title: RetailDiscountLine.OfferPriceIncludingTax Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: OfferPriceIncludingTax Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailDiscountLine.OfferPriceIncludingTax
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.retaildiscountline.offerpriceincludingtax(v=AX.60)
ms:contentKeyID: 62213133
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailDiscountLine.OfferPriceIncludingTax
dev_langs:
- CSharp
- C++
- VB
---

# OfferPriceIncludingTax Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the final discount price including tax if this is a discount offer rule.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("OFFERPRICEINCLTAX")> _
<DataMemberAttribute> _
Public Property OfferPriceIncludingTax As Decimal
    Get
    Set
'Usage
Dim instance As RetailDiscountLine
Dim value As Decimal

value = instance.OfferPriceIncludingTax

instance.OfferPriceIncludingTax = value
```

``` csharp
[ColumnAttribute("OFFERPRICEINCLTAX")]
[DataMemberAttribute]
public decimal OfferPriceIncludingTax { get; set; }
```

``` c++
[ColumnAttribute(L"OFFERPRICEINCLTAX")]
[DataMemberAttribute]
public:
property Decimal OfferPriceIncludingTax {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[RetailDiscountLine Class](retaildiscountline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

