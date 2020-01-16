---
title: ThresholdDiscount.ThresholdDiscountTiers Property  (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData)
TOCTitle: ThresholdDiscountTiers Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.ThresholdDiscount.ThresholdDiscountTiers
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingengine.discountdata.thresholddiscount.thresholddiscounttiers(v=AX.60)
ms:contentKeyID: 62202937
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.ThresholdDiscount.ThresholdDiscountTiers
dev_langs:
- CSharp
- C++
- VB
---

# ThresholdDiscountTiers Property

Gets the threshold discount tiers for this discount.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Public Property ThresholdDiscountTiers As IList(Of ThresholdDiscountTier)
    Get
    Private Set
'Usage
Dim instance As ThresholdDiscount
Dim value As IList(Of ThresholdDiscountTier)

value = instance.ThresholdDiscountTiers
```

``` csharp
public IList<ThresholdDiscountTier> ThresholdDiscountTiers { get; private set; }
```

``` c++
public:
property IList<ThresholdDiscountTier^>^ ThresholdDiscountTiers {
    IList<ThresholdDiscountTier^>^ get ();
    private: void set (IList<ThresholdDiscountTier^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IList](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\))\<[ThresholdDiscountTier](thresholddiscounttier-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [IList\<T\>](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\)).  

## See Also

#### Reference

[ThresholdDiscount Class](thresholddiscount-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)

