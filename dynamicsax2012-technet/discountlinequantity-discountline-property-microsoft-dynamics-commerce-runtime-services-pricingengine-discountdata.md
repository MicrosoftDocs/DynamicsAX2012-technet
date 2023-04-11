---
title: DiscountLineQuantity.DiscountLine Property  (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData)
TOCTitle: DiscountLine Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountLineQuantity.DiscountLine
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingengine.discountdata.discountlinequantity.discountline(v=AX.60)
ms:contentKeyID: 62204341
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountLineQuantity.DiscountLine
dev_langs:
- CSharp
- C++
- VB
---

# DiscountLine Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the discount line that belongs to the discount.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Public Property DiscountLine As DiscountLine
    Get
    Set
'Usage
Dim instance As DiscountLineQuantity
Dim value As DiscountLine

value = instance.DiscountLine

instance.DiscountLine = value
```

``` csharp
public DiscountLine DiscountLine { get; set; }
```

``` c++
public:
property DiscountLine^ DiscountLine {
    DiscountLine^ get ();
    void set (DiscountLine^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountLine](discountline-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [DiscountLine](discountline-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[DiscountLineQuantity Class](discountlinequantity-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)

