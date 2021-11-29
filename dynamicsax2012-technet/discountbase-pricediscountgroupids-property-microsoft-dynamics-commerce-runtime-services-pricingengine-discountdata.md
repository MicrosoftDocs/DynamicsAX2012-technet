---
title: DiscountBase.PriceDiscountGroupIds Property  (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData)
TOCTitle: PriceDiscountGroupIds Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountBase.PriceDiscountGroupIds
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingengine.discountdata.discountbase.pricediscountgroupids(v=AX.60)
ms:contentKeyID: 62213093
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountBase.PriceDiscountGroupIds
dev_langs:
- CSharp
- C++
- VB
---

# PriceDiscountGroupIds Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the pricing group identifiers for this discount.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Public Property PriceDiscountGroupIds As ISet(Of Long)
    Get
    Private Set
'Usage
Dim instance As DiscountBase
Dim value As ISet(Of Long)

value = instance.PriceDiscountGroupIds
```

``` csharp
public ISet<long> PriceDiscountGroupIds { get; private set; }
```

``` c++
public:
property ISet<long long>^ PriceDiscountGroupIds {
    ISet<long long>^ get ();
    private: void set (ISet<long long>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.ISet](https://technet.microsoft.com/library/dd412081\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  
Returns [ISet\<T\>](https://technet.microsoft.com/library/dd412081\(v=ax.60\)).  

## See Also

#### Reference

[DiscountBase Class](discountbase-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)

