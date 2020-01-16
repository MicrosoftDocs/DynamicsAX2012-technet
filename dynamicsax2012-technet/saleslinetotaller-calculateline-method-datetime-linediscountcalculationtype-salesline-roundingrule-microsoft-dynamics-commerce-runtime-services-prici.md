---
title: SalesLineTotaller.CalculateLine Method (DateTime, LineDiscountCalculationType, SalesLine, RoundingRule) (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine)
TOCTitle: CalculateLine Method (DateTime, LineDiscountCalculationType, SalesLine, RoundingRule)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.SalesLineTotaller.CalculateLine(System.DateTime,Microsoft.Dynamics.Commerce.Runtime.DataModel.LineDiscountCalculationType,Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine,Microsoft.Dynamics.Commerce.Runtime.DataModel.RoundingRule)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingengine.saleslinetotaller.calculateline(v=AX.60)
ms:contentKeyID: 65323002
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# CalculateLine Method (DateTime, LineDiscountCalculationType, SalesLine, RoundingRule)

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Public Shared Sub CalculateLine ( _
    transactionBeginDateTime As DateTime, _
    lineDiscountCalculationType As LineDiscountCalculationType, _
    salesLine As SalesLine, _
    salesRoundingRule As RoundingRule _
)
'Usage
Dim transactionBeginDateTime As DateTime
Dim lineDiscountCalculationType As LineDiscountCalculationType
Dim salesLine As SalesLine
Dim salesRoundingRule As RoundingRule

SalesLineTotaller.CalculateLine(transactionBeginDateTime, _
    lineDiscountCalculationType, salesLine, _
    salesRoundingRule)
```

``` csharp
public static void CalculateLine(
    DateTime transactionBeginDateTime,
    LineDiscountCalculationType lineDiscountCalculationType,
    SalesLine salesLine,
    RoundingRule salesRoundingRule
)
```

``` c++
public:
static void CalculateLine(
    DateTime transactionBeginDateTime, 
    LineDiscountCalculationType lineDiscountCalculationType, 
    SalesLine^ salesLine, 
    RoundingRule^ salesRoundingRule
)
```

#### Parameters

  - transactionBeginDateTime  
    Type: [System.DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\))  

<!-- end list -->

  - lineDiscountCalculationType  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.LineDiscountCalculationType](linediscountcalculationtype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

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

