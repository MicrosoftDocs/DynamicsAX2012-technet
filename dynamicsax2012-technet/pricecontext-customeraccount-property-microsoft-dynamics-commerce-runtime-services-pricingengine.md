---
title: PriceContext.CustomerAccount Property  (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine)
TOCTitle: CustomerAccount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContext.CustomerAccount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingengine.pricecontext.customeraccount(v=AX.60)
ms:contentKeyID: 62204351
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContext.CustomerAccount
dev_langs:
- CSharp
- C++
- VB
---

# CustomerAccount Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the customer account number for customer-specific prices. Optional.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Public Property CustomerAccount As String
    Get
    Set
'Usage
Dim instance As PriceContext
Dim value As String

value = instance.CustomerAccount

instance.CustomerAccount = value
```

``` csharp
public string CustomerAccount { get; set; }
```

``` c++
public:
property String^ CustomerAccount {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[PriceContext Class](pricecontext-class-microsoft-dynamics-commerce-runtime-services-pricingengine.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)

