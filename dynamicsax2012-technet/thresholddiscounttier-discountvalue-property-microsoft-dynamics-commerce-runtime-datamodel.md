---
title: ThresholdDiscountTier.DiscountValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DiscountValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ThresholdDiscountTier.DiscountValue
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.thresholddiscounttier.discountvalue(v=AX.60)
ms:contentKeyID: 62208943
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ThresholdDiscountTier.DiscountValue
dev_langs:
- CSharp
- C++
- VB
---

# DiscountValue Property

Gets or sets the value of the the discount given by this tier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("DISCOUNTVALUE")> _
<DataMemberAttribute> _
Public Property DiscountValue As Decimal
    Get
    Set
'Usage
Dim instance As ThresholdDiscountTier
Dim value As Decimal

value = instance.DiscountValue

instance.DiscountValue = value
```

``` csharp
[ColumnAttribute("DISCOUNTVALUE")]
[DataMemberAttribute]
public decimal DiscountValue { get; set; }
```

``` c++
[ColumnAttribute(L"DISCOUNTVALUE")]
[DataMemberAttribute]
public:
property Decimal DiscountValue {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[ThresholdDiscountTier Class](thresholddiscounttier-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

