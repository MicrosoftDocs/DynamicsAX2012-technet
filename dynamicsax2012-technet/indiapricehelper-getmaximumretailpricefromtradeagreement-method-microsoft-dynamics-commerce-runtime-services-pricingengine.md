---
title: IndiaPriceHelper.GetMaximumRetailPriceFromTradeAgreement Method  (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine)
TOCTitle: GetMaximumRetailPriceFromTradeAgreement Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.IndiaPriceHelper.GetMaximumRetailPriceFromTradeAgreement(Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingengine.indiapricehelper.getmaximumretailpricefromtradeagreement(v=AX.60)
ms:contentKeyID: 62208466
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.IndiaPriceHelper.GetMaximumRetailPriceFromTradeAgreement
dev_langs:
- CSharp
- C++
- VB
---

# GetMaximumRetailPriceFromTradeAgreement Method

Gets maximum retail price from trade agreement.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Public Function GetMaximumRetailPriceFromTradeAgreement ( _
    salesLine As SalesLine _
) As Decimal
'Usage
Dim instance As IndiaPriceHelper
Dim salesLine As SalesLine
Dim returnValue As Decimal

returnValue = instance.GetMaximumRetailPriceFromTradeAgreement(salesLine)
```

``` csharp
public decimal GetMaximumRetailPriceFromTradeAgreement(
    SalesLine salesLine
)
```

``` c++
public:
Decimal GetMaximumRetailPriceFromTradeAgreement(
    SalesLine^ salesLine
)
```

#### Parameters

  - salesLine  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Maximum retail price from trade agreement.  

## See Also

#### Reference

[IndiaPriceHelper Class](indiapricehelper-class-microsoft-dynamics-commerce-runtime-services-pricingengine.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)

