---
title: SalesLineTotaller.CalculateLine Method (SalesTransaction, SalesLine, RoundingRule) (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine)
TOCTitle: CalculateLine Method (SalesTransaction, SalesLine, RoundingRule)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.SalesLineTotaller.CalculateLine(Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction,Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine,Microsoft.Dynamics.Commerce.Runtime.DataModel.RoundingRule)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingengine.saleslinetotaller.calculateline(v=AX.60)
ms:contentKeyID: 65319281
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# CalculateLine Method (SalesTransaction, SalesLine, RoundingRule)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Public Shared Sub CalculateLine ( _
    salesTransaction As SalesTransaction, _
    salesLine As SalesLine, _
    salesRoundingRule As RoundingRule _
)
'Usage
Dim salesTransaction As SalesTransaction
Dim salesLine As SalesLine
Dim salesRoundingRule As RoundingRule

SalesLineTotaller.CalculateLine(salesTransaction, _
    salesLine, salesRoundingRule)
```

``` csharp
public static void CalculateLine(
    SalesTransaction salesTransaction,
    SalesLine salesLine,
    RoundingRule salesRoundingRule
)
```

``` c++
public:
static void CalculateLine(
    SalesTransaction^ salesTransaction, 
    SalesLine^ salesLine, 
    RoundingRule^ salesRoundingRule
)
```

#### Parameters

  - salesTransaction  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - salesLine  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - salesRoundingRule  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.RoundingRule](roundingrule-delegate-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[SalesLineTotaller Class](saleslinetotaller-class-microsoft-dynamics-commerce-runtime-services-pricingengine.md)

[CalculateLine Overload](saleslinetotaller-calculateline-method-microsoft-dynamics-commerce-runtime-services-pricingengine.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)

