---
title: PricingEngine.CalculateDiscountsForLines Method  (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine)
TOCTitle: CalculateDiscountsForLines Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PricingEngine.CalculateDiscountsForLines(Microsoft.Dynamics.Commerce.Runtime.Data.IPricingDataManagerV2,Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction,Microsoft.Dynamics.Commerce.Runtime.DataModel.RoundingRule,Microsoft.Dynamics.Commerce.Runtime.Data.CurrencyConverter,System.String,System.String,System.String,System.String,System.Boolean,Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountCalculationMode,System.DateTimeOffset)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingengine.pricingengine.calculatediscountsforlines(v=AX.60)
ms:contentKeyID: 65322716
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PricingEngine.CalculateDiscountsForLines
dev_langs:
- CSharp
- C++
- VB
---

# CalculateDiscountsForLines Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Public Shared Sub CalculateDiscountsForLines ( _
    pricingDataManager As IPricingDataManagerV2, _
    transaction As SalesTransaction, _
    roundingRule As RoundingRule, _
    currencyConverter As CurrencyConverter, _
    currencyCode As String, _
    lineDiscountGroup As String, _
    multilineDiscountGroup As String, _
    totalDiscountGroup As String, _
    shouldTotalLines As Boolean, _
    calculationMode As DiscountCalculationMode, _
    activeDate As DateTimeOffset _
)
'Usage
Dim pricingDataManager As IPricingDataManagerV2
Dim transaction As SalesTransaction
Dim roundingRule As RoundingRule
Dim currencyConverter As CurrencyConverter
Dim currencyCode As String
Dim lineDiscountGroup As String
Dim multilineDiscountGroup As String
Dim totalDiscountGroup As String
Dim shouldTotalLines As Boolean
Dim calculationMode As DiscountCalculationMode
Dim activeDate As DateTimeOffset

PricingEngine.CalculateDiscountsForLines(pricingDataManager, _
    transaction, roundingRule, currencyConverter, _
    currencyCode, lineDiscountGroup, _
    multilineDiscountGroup, totalDiscountGroup, _
    shouldTotalLines, calculationMode, _
    activeDate)
```

``` csharp
public static void CalculateDiscountsForLines(
    IPricingDataManagerV2 pricingDataManager,
    SalesTransaction transaction,
    RoundingRule roundingRule,
    CurrencyConverter currencyConverter,
    string currencyCode,
    string lineDiscountGroup,
    string multilineDiscountGroup,
    string totalDiscountGroup,
    bool shouldTotalLines,
    DiscountCalculationMode calculationMode,
    DateTimeOffset activeDate
)
```

``` c++
public:
static void CalculateDiscountsForLines(
    IPricingDataManagerV2^ pricingDataManager, 
    SalesTransaction^ transaction, 
    RoundingRule^ roundingRule, 
    CurrencyConverter^ currencyConverter, 
    String^ currencyCode, 
    String^ lineDiscountGroup, 
    String^ multilineDiscountGroup, 
    String^ totalDiscountGroup, 
    bool shouldTotalLines, 
    DiscountCalculationMode calculationMode, 
    DateTimeOffset activeDate
)
```

#### Parameters

  - pricingDataManager  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.IPricingDataManagerV2](ipricingdatamanagerv2-interface-microsoft-dynamics-commerce-runtime-data.md)  

<!-- end list -->

  - transaction  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - roundingRule  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.RoundingRule](roundingrule-delegate-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - currencyConverter  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.CurrencyConverter](currencyconverter-delegate-microsoft-dynamics-commerce-runtime-data.md)  

<!-- end list -->

  - currencyCode  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - lineDiscountGroup  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - multilineDiscountGroup  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - totalDiscountGroup  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - shouldTotalLines  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - calculationMode  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountCalculationMode](discountcalculationmode-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - activeDate  
    Type: [System.DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))  

## See Also

#### Reference

[PricingEngine Class](pricingengine-class-microsoft-dynamics-commerce-runtime-services-pricingengine.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)

