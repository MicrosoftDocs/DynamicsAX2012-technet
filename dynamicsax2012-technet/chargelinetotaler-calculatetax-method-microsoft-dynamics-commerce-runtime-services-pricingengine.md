---
title: ChargeLineTotaler.CalculateTax Method  (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine)
TOCTitle: CalculateTax Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.ChargeLineTotaler.CalculateTax(Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxableItem)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingengine.chargelinetotaler.calculatetax(v=AX.60)
ms:contentKeyID: 62204385
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.ChargeLineTotaler.CalculateTax
dev_langs:
- CSharp
- C++
- VB
---

# CalculateTax Method

Calculates the tax amount properties on this taxable item.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Public Shared Sub CalculateTax ( _
    taxableItem As TaxableItem _
)
'Usage
Dim taxableItem As TaxableItem

ChargeLineTotaler.CalculateTax(taxableItem)
```

``` csharp
public static void CalculateTax(
    TaxableItem taxableItem
)
```

``` c++
public:
static void CalculateTax(
    TaxableItem^ taxableItem
)
```

#### Parameters

  - taxableItem  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxableItem](taxableitem-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[ChargeLineTotaler Class](chargelinetotaler-class-microsoft-dynamics-commerce-runtime-services-pricingengine.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)

