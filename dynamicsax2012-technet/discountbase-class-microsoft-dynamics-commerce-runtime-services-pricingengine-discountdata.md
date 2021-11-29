---
title: DiscountBase Class (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData)
TOCTitle: DiscountBase Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountBase
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingengine.discountdata.discountbase(v=AX.60)
ms:contentKeyID: 62211948
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountBase
dev_langs:
- CSharp
- C++
- VB
---

# DiscountBase Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Abstract class containing all of the standard properties that are shared across discount types. For specific discount types, see one of the implementations of this class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Public MustInherit Class DiscountBase
'Usage
Dim instance As DiscountBase
```

``` csharp
public abstract class DiscountBase
```

``` c++
public ref class DiscountBase abstract
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountBase  
    [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.MixAndMatchDiscount](mixandmatchdiscount-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.MultipleBuyDiscount](multiplebuydiscount-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.OfferDiscount](offerdiscount-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.ThresholdDiscount](thresholddiscount-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md)  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)

