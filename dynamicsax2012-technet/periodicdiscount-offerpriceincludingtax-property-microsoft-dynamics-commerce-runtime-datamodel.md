---
title: PeriodicDiscount.OfferPriceIncludingTax Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: OfferPriceIncludingTax Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PeriodicDiscount.OfferPriceIncludingTax
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.periodicdiscount.offerpriceincludingtax(v=AX.60)
ms:contentKeyID: 49847846
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PeriodicDiscount.OfferPriceIncludingTax
dev_langs:
- CSharp
- C++
- VB
---

# OfferPriceIncludingTax Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the final discount price including tax if this is a discount offer rule.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("OFFERPRICEINCLTAX")> _
Public Property OfferPriceIncludingTax As Decimal
    Get
    Friend Set
'Usage
Dim instance As PeriodicDiscount
Dim value As Decimal

value = instance.OfferPriceIncludingTax
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("OFFERPRICEINCLTAX")]
public decimal OfferPriceIncludingTax { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"OFFERPRICEINCLTAX")]
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

[PeriodicDiscount Class](periodicdiscount-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

