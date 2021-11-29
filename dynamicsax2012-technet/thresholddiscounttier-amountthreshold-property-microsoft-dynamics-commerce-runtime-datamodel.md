---
title: ThresholdDiscountTier.AmountThreshold Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AmountThreshold Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ThresholdDiscountTier.AmountThreshold
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.thresholddiscounttier.amountthreshold(v=AX.60)
ms:contentKeyID: 62212497
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ThresholdDiscountTier.AmountThreshold
dev_langs:
- CSharp
- C++
- VB
---

# AmountThreshold Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the amount which triggers this tier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("AMOUNTTHRESHOLD")> _
<DataMemberAttribute> _
Public Property AmountThreshold As Decimal
    Get
    Set
'Usage
Dim instance As ThresholdDiscountTier
Dim value As Decimal

value = instance.AmountThreshold

instance.AmountThreshold = value
```

``` csharp
[ColumnAttribute("AMOUNTTHRESHOLD")]
[DataMemberAttribute]
public decimal AmountThreshold { get; set; }
```

``` c++
[ColumnAttribute(L"AMOUNTTHRESHOLD")]
[DataMemberAttribute]
public:
property Decimal AmountThreshold {
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

