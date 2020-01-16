---
title: PricingEngine.GetAllPeriodicDiscountsForLines Method  (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine)
TOCTitle: GetAllPeriodicDiscountsForLines Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PricingEngine.GetAllPeriodicDiscountsForLines(Microsoft.Dynamics.Commerce.Runtime.Data.IPricingDataManagerV2,Microsoft.Dynamics.Commerce.Runtime.DataModel.RoundingRule,Microsoft.Dynamics.Commerce.Runtime.Data.CurrencyConverter,Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction,System.String,System.DateTimeOffset,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingengine.pricingengine.getallperiodicdiscountsforlines(v=AX.60)
ms:contentKeyID: 65321806
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PricingEngine.GetAllPeriodicDiscountsForLines
dev_langs:
- CSharp
- C++
- VB
---

# GetAllPeriodicDiscountsForLines Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Public Shared Sub GetAllPeriodicDiscountsForLines ( _
    pricingDataManager As IPricingDataManagerV2, _
    rounding As RoundingRule, _
    currencyConverter As CurrencyConverter, _
    transaction As SalesTransaction, _
    currencyCode As String, _
    activeDate As DateTimeOffset, _
    doesPriceIncludeTax As Boolean _
)
'Usage
Dim pricingDataManager As IPricingDataManagerV2
Dim rounding As RoundingRule
Dim currencyConverter As CurrencyConverter
Dim transaction As SalesTransaction
Dim currencyCode As String
Dim activeDate As DateTimeOffset
Dim doesPriceIncludeTax As Boolean

PricingEngine.GetAllPeriodicDiscountsForLines(pricingDataManager, _
    rounding, currencyConverter, transaction, _
    currencyCode, activeDate, doesPriceIncludeTax)
```

``` csharp
public static void GetAllPeriodicDiscountsForLines(
    IPricingDataManagerV2 pricingDataManager,
    RoundingRule rounding,
    CurrencyConverter currencyConverter,
    SalesTransaction transaction,
    string currencyCode,
    DateTimeOffset activeDate,
    bool doesPriceIncludeTax
)
```

``` c++
public:
static void GetAllPeriodicDiscountsForLines(
    IPricingDataManagerV2^ pricingDataManager, 
    RoundingRule^ rounding, 
    CurrencyConverter^ currencyConverter, 
    SalesTransaction^ transaction, 
    String^ currencyCode, 
    DateTimeOffset activeDate, 
    bool doesPriceIncludeTax
)
```

#### Parameters

  - pricingDataManager  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.IPricingDataManagerV2](ipricingdatamanagerv2-interface-microsoft-dynamics-commerce-runtime-data.md)  

<!-- end list -->

  - rounding  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.RoundingRule](roundingrule-delegate-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - currencyConverter  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.CurrencyConverter](currencyconverter-delegate-microsoft-dynamics-commerce-runtime-data.md)  

<!-- end list -->

  - transaction  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - currencyCode  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - activeDate  
    Type: [System.DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))  

<!-- end list -->

  - doesPriceIncludeTax  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[PricingEngine Class](pricingengine-class-microsoft-dynamics-commerce-runtime-services-pricingengine.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)

