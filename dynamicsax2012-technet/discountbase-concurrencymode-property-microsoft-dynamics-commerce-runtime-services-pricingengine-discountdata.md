---
title: DiscountBase.ConcurrencyMode Property  (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData)
TOCTitle: ConcurrencyMode Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountBase.ConcurrencyMode
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingengine.discountdata.discountbase.concurrencymode(v=AX.60)
ms:contentKeyID: 62205738
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountBase.ConcurrencyMode
dev_langs:
- CSharp
- C++
- VB
---

# ConcurrencyMode Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the concurrency mode for this discount (exclusive, best-price, compound).

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Public Property ConcurrencyMode As ConcurrencyMode
    Get
    Set
'Usage
Dim instance As DiscountBase
Dim value As ConcurrencyMode

value = instance.ConcurrencyMode

instance.ConcurrencyMode = value
```

``` csharp
public ConcurrencyMode ConcurrencyMode { get; set; }
```

``` c++
public:
property ConcurrencyMode ConcurrencyMode {
    ConcurrencyMode get ();
    void set (ConcurrencyMode value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ConcurrencyMode](concurrencymode-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [ConcurrencyMode](concurrencymode-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[DiscountBase Class](discountbase-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)

