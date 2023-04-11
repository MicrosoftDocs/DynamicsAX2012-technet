---
title: ThresholdDiscount Class (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData)
TOCTitle: ThresholdDiscount Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.ThresholdDiscount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingengine.discountdata.thresholddiscount(v=AX.60)
ms:contentKeyID: 62214945
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.ThresholdDiscount
dev_langs:
- CSharp
- C++
- VB
---

# ThresholdDiscount Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

This class implements the threshold (by amount) discount processing, including the determination of which ways the discount can apply to the transaction and the value of the discount applied to specific lines.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Public Class ThresholdDiscount _
    Inherits DiscountBase
'Usage
Dim instance As ThresholdDiscount
```

``` csharp
public class ThresholdDiscount : DiscountBase
```

``` c++
public ref class ThresholdDiscount : public DiscountBase
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountBase](discountbase-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md)  
    Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.ThresholdDiscount  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)

