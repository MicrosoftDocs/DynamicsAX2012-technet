---
title: RetailDiscount.MixAndMatchDiscountPercent Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: MixAndMatchDiscountPercent Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailDiscount.MixAndMatchDiscountPercent
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.retaildiscount.mixandmatchdiscountpercent(v=AX.60)
ms:contentKeyID: 62212427
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailDiscount.MixAndMatchDiscountPercent
dev_langs:
- CSharp
- C++
- VB
---

# MixAndMatchDiscountPercent Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the percent off of a mix and match set if this is a mix and match discount.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("DISCOUNTPERCENTVALUE")> _
Public Property MixAndMatchDiscountPercent As Decimal
    Get
    Set
'Usage
Dim instance As RetailDiscount
Dim value As Decimal

value = instance.MixAndMatchDiscountPercent

instance.MixAndMatchDiscountPercent = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("DISCOUNTPERCENTVALUE")]
public decimal MixAndMatchDiscountPercent { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"DISCOUNTPERCENTVALUE")]
public:
property Decimal MixAndMatchDiscountPercent {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[RetailDiscount Class](retaildiscount-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

