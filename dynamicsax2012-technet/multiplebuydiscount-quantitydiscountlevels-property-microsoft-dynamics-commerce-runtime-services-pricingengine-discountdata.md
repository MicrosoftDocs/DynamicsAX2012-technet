---
title: MultipleBuyDiscount.QuantityDiscountLevels Property  (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData)
TOCTitle: QuantityDiscountLevels Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.MultipleBuyDiscount.QuantityDiscountLevels
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingengine.discountdata.multiplebuydiscount.quantitydiscountlevels(v=AX.60)
ms:contentKeyID: 62210427
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.MultipleBuyDiscount.QuantityDiscountLevels
dev_langs:
- CSharp
- C++
- VB
---

# QuantityDiscountLevels Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Public Property QuantityDiscountLevels As IList(Of QuantityDiscountLevel)
    Get
    Private Set
'Usage
Dim instance As MultipleBuyDiscount
Dim value As IList(Of QuantityDiscountLevel)

value = instance.QuantityDiscountLevels
```

``` csharp
public IList<QuantityDiscountLevel> QuantityDiscountLevels { get; private set; }
```

``` c++
public:
property IList<QuantityDiscountLevel^>^ QuantityDiscountLevels {
    IList<QuantityDiscountLevel^>^ get ();
    private: void set (IList<QuantityDiscountLevel^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IList](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\))\<[QuantityDiscountLevel](quantitydiscountlevel-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[MultipleBuyDiscount Class](multiplebuydiscount-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)

