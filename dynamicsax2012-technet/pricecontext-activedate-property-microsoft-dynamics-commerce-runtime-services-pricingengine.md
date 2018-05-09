---
title: PriceContext.ActiveDate Property  (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine)
TOCTitle: ActiveDate Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContext.ActiveDate
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.pricingengine.pricecontext.activedate(v=AX.60)
ms:contentKeyID: 62210991
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContext.ActiveDate
dev_langs:
- CSharp
- C++
- VB
---

# ActiveDate Property

Gets or sets the date and time on which to calculate the prices.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Public Property ActiveDate As DateTimeOffset
    Get
    Set
'Usage
Dim instance As PriceContext
Dim value As DateTimeOffset

value = instance.ActiveDate

instance.ActiveDate = value
```

``` csharp
public DateTimeOffset ActiveDate { get; set; }
```

``` c++
public:
property DateTimeOffset ActiveDate {
    DateTimeOffset get ();
    void set (DateTimeOffset value);
}
```

#### Property Value

Type: [System.DateTimeOffset](https://technet.microsoft.com/en-us/library/bb341783\(v=ax.60\))  
Returns [DateTimeOffset](https://technet.microsoft.com/en-us/library/bb341783\(v=ax.60\)).  

## See Also

#### Reference

[PriceContext Class](pricecontext-class-microsoft-dynamics-commerce-runtime-services-pricingengine.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)

