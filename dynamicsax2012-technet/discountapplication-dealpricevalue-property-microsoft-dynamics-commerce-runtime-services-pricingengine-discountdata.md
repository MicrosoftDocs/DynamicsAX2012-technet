---
title: DiscountApplication.DealPriceValue Property  (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData)
TOCTitle: DealPriceValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountApplication.DealPriceValue
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingengine.discountdata.discountapplication.dealpricevalue(v=AX.60)
ms:contentKeyID: 62204780
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountApplication.DealPriceValue
dev_langs:
- CSharp
- C++
- VB
---

# DealPriceValue Property

Gets or sets the application-specific deal or unit price value.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Public Property DealPriceValue As Decimal
    Get
    Set
'Usage
Dim instance As DiscountApplication
Dim value As Decimal

value = instance.DealPriceValue

instance.DealPriceValue = value
```

``` csharp
public decimal DealPriceValue { get; set; }
```

``` c++
public:
property Decimal DealPriceValue {
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

