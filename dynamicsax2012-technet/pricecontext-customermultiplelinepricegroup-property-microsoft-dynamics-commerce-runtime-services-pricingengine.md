---
title: PriceContext.CustomerMultipleLinePriceGroup Property  (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine)
TOCTitle: CustomerMultipleLinePriceGroup Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContext.CustomerMultipleLinePriceGroup
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingengine.pricecontext.customermultiplelinepricegroup(v=AX.60)
ms:contentKeyID: 62206263
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContext.CustomerMultipleLinePriceGroup
dev_langs:
- CSharp
- C++
- VB
---

# CustomerMultipleLinePriceGroup Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the customer multiple line discount price group Id for customer-specific prices. Optional.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Public Property CustomerMultipleLinePriceGroup As String
    Get
    Set
'Usage
Dim instance As PriceContext
Dim value As String

value = instance.CustomerMultipleLinePriceGroup

instance.CustomerMultipleLinePriceGroup = value
```

``` csharp
public string CustomerMultipleLinePriceGroup { get; set; }
```

``` c++
public:
property String^ CustomerMultipleLinePriceGroup {
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

