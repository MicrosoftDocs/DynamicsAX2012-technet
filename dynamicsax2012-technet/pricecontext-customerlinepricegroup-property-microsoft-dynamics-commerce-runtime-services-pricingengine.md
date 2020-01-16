---
title: PriceContext.CustomerLinePriceGroup Property  (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine)
TOCTitle: CustomerLinePriceGroup Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContext.CustomerLinePriceGroup
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingengine.pricecontext.customerlinepricegroup(v=AX.60)
ms:contentKeyID: 62212853
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContext.CustomerLinePriceGroup
dev_langs:
- CSharp
- C++
- VB
---

# CustomerLinePriceGroup Property

Gets or sets the customer line discount price group Id for customer-specific prices. Optional.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Public Property CustomerLinePriceGroup As String
    Get
    Set
'Usage
Dim instance As PriceContext
Dim value As String

value = instance.CustomerLinePriceGroup

instance.CustomerLinePriceGroup = value
```

``` csharp
public string CustomerLinePriceGroup { get; set; }
```

``` c++
public:
property String^ CustomerLinePriceGroup {
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

