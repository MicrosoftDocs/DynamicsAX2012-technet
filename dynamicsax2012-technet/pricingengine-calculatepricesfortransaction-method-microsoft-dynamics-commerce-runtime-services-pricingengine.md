---
title: PricingEngine.CalculatePricesForTransaction Method  (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine)
TOCTitle: CalculatePricesForTransaction Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PricingEngine.CalculatePricesForTransaction(Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction,Microsoft.Dynamics.Commerce.Runtime.Data.IPricingDataManagerV2,Microsoft.Dynamics.Commerce.Runtime.DataModel.RoundingRule,Microsoft.Dynamics.Commerce.Runtime.Data.CurrencyConverter,System.String,System.String,System.Boolean,System.DateTimeOffset)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingengine.pricingengine.calculatepricesfortransaction(v=AX.60)
ms:contentKeyID: 65320673
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PricingEngine.CalculatePricesForTransaction
dev_langs:
- CSharp
- C++
- VB
---

# CalculatePricesForTransaction Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Public Shared Sub CalculatePricesForTransaction ( _
    salesTransaction As SalesTransaction, _
    pricingDataManager As IPricingDataManagerV2, _
    roundingRule As RoundingRule, _
    currencyConverter As CurrencyConverter, _
    customerPriceGroup As String, _
    currencyCode As String, _
    allowParallelProcessing As Boolean, _
    activeDate As DateTimeOffset _
)
'Usage
Dim salesTransaction As SalesTransaction
Dim pricingDataManager As IPricingDataManagerV2
Dim roundingRule As RoundingRule
Dim currencyConverter As CurrencyConverter
Dim customerPriceGroup As String
Dim currencyCode As String
Dim allowParallelProcessing As Boolean
Dim activeDate As DateTimeOffset

PricingEngine.CalculatePricesForTransaction(salesTransaction, _
    pricingDataManager, roundingRule, _
    currencyConverter, customerPriceGroup, _
    currencyCode, allowParallelProcessing, _
    activeDate)
```

``` csharp
public static void CalculatePricesForTransaction(
    SalesTransaction salesTransaction,
    IPricingDataManagerV2 pricingDataManager,
    RoundingRule roundingRule,
    CurrencyConverter currencyConverter,
    string customerPriceGroup,
    string currencyCode,
    bool allowParallelProcessing,
    DateTimeOffset activeDate
)
```

``` c++
public:
static void CalculatePricesForTransaction(
    SalesTransaction^ salesTransaction, 
    IPricingDataManagerV2^ pricingDataManager, 
    RoundingRule^ roundingRule, 
    CurrencyConverter^ currencyConverter, 
    String^ customerPriceGroup, 
    String^ currencyCode, 
    bool allowParallelProcessing, 
    DateTimeOffset activeDate
)
```

#### Parameters

  - salesTransaction  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - pricingDataManager  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.IPricingDataManagerV2](ipricingdatamanagerv2-interface-microsoft-dynamics-commerce-runtime-data.md)  

<!-- end list -->

  - roundingRule  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.RoundingRule](roundingrule-delegate-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - currencyConverter  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.CurrencyConverter](currencyconverter-delegate-microsoft-dynamics-commerce-runtime-data.md)  

<!-- end list -->

  - customerPriceGroup  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - currencyCode  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - allowParallelProcessing  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - activeDate  
    Type: [System.DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))  

## See Also

#### Reference

[PricingEngine Class](pricingengine-class-microsoft-dynamics-commerce-runtime-services-pricingengine.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)

