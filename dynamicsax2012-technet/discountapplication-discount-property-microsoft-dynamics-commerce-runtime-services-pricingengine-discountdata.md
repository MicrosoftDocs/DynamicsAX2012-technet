---
title: DiscountApplication.Discount Property  (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData)
TOCTitle: Discount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountApplication.Discount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingengine.discountdata.discountapplication.discount(v=AX.60)
ms:contentKeyID: 62211019
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountApplication.Discount
dev_langs:
- CSharp
- C++
- VB
---

# Discount Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the discount associated with this application.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Public Property Discount As DiscountBase
    Get
    Private Set
'Usage
Dim instance As DiscountApplication
Dim value As DiscountBase

value = instance.Discount
```

``` csharp
public DiscountBase Discount { get; private set; }
```

``` c++
public:
property DiscountBase^ Discount {
    DiscountBase^ get ();
    private: void set (DiscountBase^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountBase](discountbase-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md)  
Returns [DiscountBase](discountbase-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md).  

## See Also

#### Reference

[DiscountApplication Class](discountapplication-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)

