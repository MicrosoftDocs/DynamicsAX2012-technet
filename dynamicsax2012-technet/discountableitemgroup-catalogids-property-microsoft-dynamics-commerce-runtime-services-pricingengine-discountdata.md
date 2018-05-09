---
title: DiscountableItemGroup.CatalogIds Property  (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData)
TOCTitle: CatalogIds Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountableItemGroup.CatalogIds
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.pricingengine.discountdata.discountableitemgroup.catalogids(v=AX.60)
ms:contentKeyID: 62210508
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountableItemGroup.CatalogIds
dev_langs:
- CSharp
- C++
- VB
---

# CatalogIds Property

Gets the catalog identifier from the collection of SalesLines.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Public ReadOnly Property CatalogIds As ISet(Of Long)
    Get
'Usage
Dim instance As DiscountableItemGroup
Dim value As ISet(Of Long)

value = instance.CatalogIds
```

``` csharp
public ISet<long> CatalogIds { get; }
```

``` c++
public:
property ISet<long long>^ CatalogIds {
    ISet<long long>^ get ();
}
```

#### Property Value

Type: [System.Collections.Generic.ISet](https://technet.microsoft.com/en-us/library/dd412081\(v=ax.60\))\<[Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))\>  
Returns [ISet\<T\>](https://technet.microsoft.com/en-us/library/dd412081\(v=ax.60\)).  

## See Also

#### Reference

[DiscountableItemGroup Class](discountableitemgroup-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)

