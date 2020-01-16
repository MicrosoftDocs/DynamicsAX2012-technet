---
title: PricingEngine.CalculatePricesForSalesLines Method  (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine)
TOCTitle: CalculatePricesForSalesLines Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PricingEngine.CalculatePricesForSalesLines(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine},Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContext,Microsoft.Dynamics.Commerce.Runtime.Data.IPricingDataManagerV2)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingengine.pricingengine.calculatepricesforsaleslines(v=AX.60)
ms:contentKeyID: 62210218
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PricingEngine.CalculatePricesForSalesLines
dev_langs:
- CSharp
- C++
- VB
---

# CalculatePricesForSalesLines Method

This method will calculate the prices for each of the given item lines within the given price context.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Public Shared Sub CalculatePricesForSalesLines ( _
    salesLines As IEnumerable(Of SalesLine), _
    priceContext As PriceContext, _
    pricingDataManager As IPricingDataManagerV2 _
)
'Usage
Dim salesLines As IEnumerable(Of SalesLine)
Dim priceContext As PriceContext
Dim pricingDataManager As IPricingDataManagerV2

PricingEngine.CalculatePricesForSalesLines(salesLines, _
    priceContext, pricingDataManager)
```

``` csharp
public static void CalculatePricesForSalesLines(
    IEnumerable<SalesLine> salesLines,
    PriceContext priceContext,
    IPricingDataManagerV2 pricingDataManager
)
```

``` c++
public:
static void CalculatePricesForSalesLines(
    IEnumerable<SalesLine^>^ salesLines, 
    PriceContext^ priceContext, 
    IPricingDataManagerV2^ pricingDataManager
)
```

#### Parameters

  - salesLines  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[SalesLine](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

<!-- end list -->

  - priceContext  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContext](pricecontext-class-microsoft-dynamics-commerce-runtime-services-pricingengine.md)  

<!-- end list -->

  - pricingDataManager  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.IPricingDataManagerV2](ipricingdatamanagerv2-interface-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[PricingEngine Class](pricingengine-class-microsoft-dynamics-commerce-runtime-services-pricingengine.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)

