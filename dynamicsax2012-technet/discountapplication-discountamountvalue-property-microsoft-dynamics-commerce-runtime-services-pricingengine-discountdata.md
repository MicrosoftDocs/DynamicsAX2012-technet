---
title: DiscountApplication.DiscountAmountValue Property  (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData)
TOCTitle: DiscountAmountValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountApplication.DiscountAmountValue
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingengine.discountdata.discountapplication.discountamountvalue(v=AX.60)
ms:contentKeyID: 62207928
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountApplication.DiscountAmountValue
dev_langs:
- CSharp
- C++
- VB
---

# DiscountAmountValue Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the application-specific discount amount value.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Public Property DiscountAmountValue As Decimal
    Get
    Set
'Usage
Dim instance As DiscountApplication
Dim value As Decimal

value = instance.DiscountAmountValue

instance.DiscountAmountValue = value
```

``` csharp
public decimal DiscountAmountValue { get; set; }
```

``` c++
public:
property Decimal DiscountAmountValue {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[DiscountApplication Class](discountapplication-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)

