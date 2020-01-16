---
title: PriceContextHelper.CreatePriceContext Method (RequestContext, IPricingDataManagerV2, SalesTransaction, PriceParameters, RoundingRule, CurrencyConverter, DateTimeOffset, String, String, Boolean, PricingCalculationMode, DiscountCalculationMode) (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine)
TOCTitle: CreatePriceContext Method (RequestContext, IPricingDataManagerV2, SalesTransaction, PriceParameters, RoundingRule, CurrencyConverter, DateTimeOffset, String, String, Boolean, PricingCalculationMode, DiscountCalculationMode)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContextHelper.CreatePriceContext(Microsoft.Dynamics.Commerce.Runtime.RequestContext,Microsoft.Dynamics.Commerce.Runtime.Data.IPricingDataManagerV2,Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction,Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceParameters,Microsoft.Dynamics.Commerce.Runtime.DataModel.RoundingRule,Microsoft.Dynamics.Commerce.Runtime.Data.CurrencyConverter,System.DateTimeOffset,System.String,System.String,System.Boolean,Microsoft.Dynamics.Commerce.Runtime.DataModel.PricingCalculationMode,Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountCalculationMode)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingengine.pricecontexthelper.createpricecontext(v=AX.60)
ms:contentKeyID: 65319424
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# CreatePriceContext Method (RequestContext, IPricingDataManagerV2, SalesTransaction, PriceParameters, RoundingRule, CurrencyConverter, DateTimeOffset, String, String, Boolean, PricingCalculationMode, DiscountCalculationMode)

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Public Shared Function CreatePriceContext ( _
    requestContext As RequestContext, _
    pricingDataManager As IPricingDataManagerV2, _
    transaction As SalesTransaction, _
    priceParameters As PriceParameters, _
    rounding As RoundingRule, _
    currencyConverter As CurrencyConverter, _
    activeDate As DateTimeOffset, _
    customerId As String, _
    customerPriceGroup As String, _
    priceIncludesTax As Boolean, _
    priceCalculationMode As PricingCalculationMode, _
    discountCalculationMode As DiscountCalculationMode _
) As PriceContext
'Usage
Dim requestContext As RequestContext
Dim pricingDataManager As IPricingDataManagerV2
Dim transaction As SalesTransaction
Dim priceParameters As PriceParameters
Dim rounding As RoundingRule
Dim currencyConverter As CurrencyConverter
Dim activeDate As DateTimeOffset
Dim customerId As String
Dim customerPriceGroup As String
Dim priceIncludesTax As Boolean
Dim priceCalculationMode As PricingCalculationMode
Dim discountCalculationMode As DiscountCalculationMode
Dim returnValue As PriceContext

returnValue = PriceContextHelper.CreatePriceContext(requestContext, _
    pricingDataManager, transaction, _
    priceParameters, rounding, currencyConverter, _
    activeDate, customerId, customerPriceGroup, _
    priceIncludesTax, priceCalculationMode, _
    discountCalculationMode)
```

``` csharp
public static PriceContext CreatePriceContext(
    RequestContext requestContext,
    IPricingDataManagerV2 pricingDataManager,
    SalesTransaction transaction,
    PriceParameters priceParameters,
    RoundingRule rounding,
    CurrencyConverter currencyConverter,
    DateTimeOffset activeDate,
    string customerId,
    string customerPriceGroup,
    bool priceIncludesTax,
    PricingCalculationMode priceCalculationMode,
    DiscountCalculationMode discountCalculationMode
)
```

``` c++
public:
static PriceContext^ CreatePriceContext(
    RequestContext^ requestContext, 
    IPricingDataManagerV2^ pricingDataManager, 
    SalesTransaction^ transaction, 
    PriceParameters^ priceParameters, 
    RoundingRule^ rounding, 
    CurrencyConverter^ currencyConverter, 
    DateTimeOffset activeDate, 
    String^ customerId, 
    String^ customerPriceGroup, 
    bool priceIncludesTax, 
    PricingCalculationMode priceCalculationMode, 
    DiscountCalculationMode discountCalculationMode
)
```

#### Parameters

  - requestContext  
    Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - pricingDataManager  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.IPricingDataManagerV2](ipricingdatamanagerv2-interface-microsoft-dynamics-commerce-runtime-data.md)  

<!-- end list -->

  - transaction  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - priceParameters  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceParameters](priceparameters-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - rounding  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.RoundingRule](roundingrule-delegate-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - currencyConverter  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.CurrencyConverter](currencyconverter-delegate-microsoft-dynamics-commerce-runtime-data.md)  

<!-- end list -->

  - activeDate  
    Type: [System.DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))  

<!-- end list -->

  - customerId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - customerPriceGroup  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - priceIncludesTax  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - priceCalculationMode  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.PricingCalculationMode](pricingcalculationmode-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - discountCalculationMode  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountCalculationMode](discountcalculationmode-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContext](pricecontext-class-microsoft-dynamics-commerce-runtime-services-pricingengine.md)  

## See Also

#### Reference

[PriceContextHelper Class](pricecontexthelper-class-microsoft-dynamics-commerce-runtime-services-pricingengine.md)

[CreatePriceContext Overload](pricecontexthelper-createpricecontext-method-microsoft-dynamics-commerce-runtime-services-pricingengine.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)

