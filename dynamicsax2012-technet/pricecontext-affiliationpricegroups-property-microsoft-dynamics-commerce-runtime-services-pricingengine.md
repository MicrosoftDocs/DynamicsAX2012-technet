---
title: PriceContext.AffiliationPriceGroups Property  (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine)
TOCTitle: AffiliationPriceGroups Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContext.AffiliationPriceGroups
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingengine.pricecontext.affiliationpricegroups(v=AX.60)
ms:contentKeyID: 62212434
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContext.AffiliationPriceGroups
dev_langs:
- CSharp
- C++
- VB
---

# AffiliationPriceGroups Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the collection of catalog price groups to search by.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Public Property AffiliationPriceGroups As ISet(Of String)
    Get
    Private Set
'Usage
Dim instance As PriceContext
Dim value As ISet(Of String)

value = instance.AffiliationPriceGroups
```

``` csharp
public ISet<string> AffiliationPriceGroups { get; private set; }
```

``` c++
public:
property ISet<String^>^ AffiliationPriceGroups {
    ISet<String^>^ get ();
    private: void set (ISet<String^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.ISet](https://technet.microsoft.com/library/dd412081\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  
Returns [ISet\<T\>](https://technet.microsoft.com/library/dd412081\(v=ax.60\)).  

## See Also

#### Reference

[PriceContext Class](pricecontext-class-microsoft-dynamics-commerce-runtime-services-pricingengine.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)

