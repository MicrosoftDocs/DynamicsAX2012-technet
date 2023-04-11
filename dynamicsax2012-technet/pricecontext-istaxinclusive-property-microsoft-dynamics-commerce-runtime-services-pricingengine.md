---
title: PriceContext.IsTaxInclusive Property  (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine)
TOCTitle: IsTaxInclusive Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContext.IsTaxInclusive
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingengine.pricecontext.istaxinclusive(v=AX.60)
ms:contentKeyID: 62214967
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContext.IsTaxInclusive
dev_langs:
- CSharp
- C++
- VB
---

# IsTaxInclusive Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether prices are fetched in tax-inclusive (e.g. VAT) channel or tax-exclusive (e.g. US taxes).

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Public Property IsTaxInclusive As Boolean
    Get
    Set
'Usage
Dim instance As PriceContext
Dim value As Boolean

value = instance.IsTaxInclusive

instance.IsTaxInclusive = value
```

``` csharp
public bool IsTaxInclusive { get; set; }
```

``` c++
public:
property bool IsTaxInclusive {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[PriceContext Class](pricecontext-class-microsoft-dynamics-commerce-runtime-services-pricingengine.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)

