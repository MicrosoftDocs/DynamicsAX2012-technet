---
title: DiscountLineQuantity Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData)
TOCTitle: DiscountLineQuantity Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountLineQuantity.#ctor(Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountLine,System.Decimal)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingengine.discountdata.discountlinequantity.discountlinequantity(v=AX.60)
ms:contentKeyID: 65320234
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountLineQuantity.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# DiscountLineQuantity Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    discountLine As DiscountLine, _
    quantity As Decimal _
)
'Usage
Dim discountLine As DiscountLine
Dim quantity As Decimal

Dim instance As New DiscountLineQuantity(discountLine, _
    quantity)
```

``` csharp
public DiscountLineQuantity(
    DiscountLine discountLine,
    decimal quantity
)
```

``` c++
public:
DiscountLineQuantity(
    DiscountLine^ discountLine, 
    Decimal quantity
)
```

#### Parameters

  - discountLine  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountLine](discountline-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - quantity  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

## See Also

#### Reference

[DiscountLineQuantity Class](discountlinequantity-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)

