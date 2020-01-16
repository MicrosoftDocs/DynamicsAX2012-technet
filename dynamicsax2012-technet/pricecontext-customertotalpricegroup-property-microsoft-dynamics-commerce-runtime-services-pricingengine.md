---
title: PriceContext.CustomerTotalPriceGroup Property  (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine)
TOCTitle: CustomerTotalPriceGroup Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContext.CustomerTotalPriceGroup
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingengine.pricecontext.customertotalpricegroup(v=AX.60)
ms:contentKeyID: 62201845
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContext.CustomerTotalPriceGroup
dev_langs:
- CSharp
- C++
- VB
---

# CustomerTotalPriceGroup Property

Gets or sets the customer multiple line discount price group Id for customer-specific prices. Optional.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Public Property CustomerTotalPriceGroup As String
    Get
    Set
'Usage
Dim instance As PriceContext
Dim value As String

value = instance.CustomerTotalPriceGroup

instance.CustomerTotalPriceGroup = value
```

``` csharp
public string CustomerTotalPriceGroup { get; set; }
```

``` c++
public:
property String^ CustomerTotalPriceGroup {
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

