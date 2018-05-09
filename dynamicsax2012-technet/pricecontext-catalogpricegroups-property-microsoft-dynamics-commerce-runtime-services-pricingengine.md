---
title: PriceContext.CatalogPriceGroups Property  (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine)
TOCTitle: CatalogPriceGroups Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContext.CatalogPriceGroups
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.pricingengine.pricecontext.catalogpricegroups(v=AX.60)
ms:contentKeyID: 62212991
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContext.CatalogPriceGroups
dev_langs:
- CSharp
- C++
- VB
---

# CatalogPriceGroups Property

Gets the collection of catalog price groups to search by.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Public Property CatalogPriceGroups As IDictionary(Of Long, ISet(Of String))
    Get
    Private Set
'Usage
Dim instance As PriceContext
Dim value As IDictionary(Of Long, ISet(Of String))

value = instance.CatalogPriceGroups
```

``` csharp
public IDictionary<long, ISet<string>> CatalogPriceGroups { get; private set; }
```

``` c++
public:
property IDictionary<long long, ISet<String^>^>^ CatalogPriceGroups {
    IDictionary<long long, ISet<String^>^>^ get ();
    private: void set (IDictionary<long long, ISet<String^>^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IDictionary](https://technet.microsoft.com/en-us/library/s4ys34ea\(v=ax.60\))\<[Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\)), [ISet](https://technet.microsoft.com/en-us/library/dd412081\(v=ax.60\))\<[String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))\>\>  
Returns [IDictionary\<TKey, TValue\>](https://technet.microsoft.com/en-us/library/s4ys34ea\(v=ax.60\)).  

## Remarks

For catalog specific discounts, we need to ensure discounted items are in the catalogs.

Hence, given discount price groups, we need to figure out whether an item is qualified if the discount is catalog only.

More details in PriceContextHelper in price engine.

## See Also

#### Reference

[PriceContext Class](pricecontext-class-microsoft-dynamics-commerce-runtime-services-pricingengine.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)

