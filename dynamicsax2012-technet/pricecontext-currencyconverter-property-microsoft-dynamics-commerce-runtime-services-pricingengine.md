---
title: PriceContext.CurrencyConverter Property  (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine)
TOCTitle: CurrencyConverter Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContext.CurrencyConverter
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingengine.pricecontext.currencyconverter(v=AX.60)
ms:contentKeyID: 62204004
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContext.CurrencyConverter
dev_langs:
- CSharp
- C++
- VB
---

# CurrencyConverter Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the currency converter delegate.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Public Property CurrencyConverter As CurrencyConverter
    Get
    Set
'Usage
Dim instance As PriceContext
Dim value As CurrencyConverter

value = instance.CurrencyConverter

instance.CurrencyConverter = value
```

``` csharp
public CurrencyConverter CurrencyConverter { get; set; }
```

``` c++
public:
property CurrencyConverter^ CurrencyConverter {
    CurrencyConverter^ get ();
    void set (CurrencyConverter^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Data.CurrencyConverter](currencyconverter-delegate-microsoft-dynamics-commerce-runtime-data.md)  
Returns [CurrencyConverter](currencyconverter-delegate-microsoft-dynamics-commerce-runtime-data.md).  

## See Also

#### Reference

[PriceContext Class](pricecontext-class-microsoft-dynamics-commerce-runtime-services-pricingengine.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)

