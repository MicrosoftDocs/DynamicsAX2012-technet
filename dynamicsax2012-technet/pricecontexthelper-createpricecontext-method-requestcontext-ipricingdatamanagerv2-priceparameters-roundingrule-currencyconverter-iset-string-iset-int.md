---
title: PriceContextHelper.CreatePriceContext Method (RequestContext, IPricingDataManagerV2, PriceParameters, RoundingRule, CurrencyConverter, ISet(String), ISet(Int64), DateTimeOffset, PricingCalculationMode, DiscountCalculationMode) (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine)
TOCTitle: CreatePriceContext Method (RequestContext, IPricingDataManagerV2, PriceParameters, RoundingRule, CurrencyConverter, ISet(String), ISet(Int64), DateTimeOffset, PricingCalculationMode, DiscountCalculationMode)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContextHelper.CreatePriceContext(Microsoft.Dynamics.Commerce.Runtime.RequestContext,Microsoft.Dynamics.Commerce.Runtime.Data.IPricingDataManagerV2,Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceParameters,Microsoft.Dynamics.Commerce.Runtime.DataModel.RoundingRule,Microsoft.Dynamics.Commerce.Runtime.Data.CurrencyConverter,System.Collections.Generic.ISet{System.String},System.Collections.Generic.ISet{System.Int64},System.DateTimeOffset,Microsoft.Dynamics.Commerce.Runtime.DataModel.PricingCalculationMode,Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountCalculationMode)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingengine.pricecontexthelper.createpricecontext(v=AX.60)
ms:contentKeyID: 65317363
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# CreatePriceContext Method (RequestContext, IPricingDataManagerV2, PriceParameters, RoundingRule, CurrencyConverter, ISet(String), ISet(Int64), DateTimeOffset, PricingCalculationMode, DiscountCalculationMode)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Public Shared Function CreatePriceContext ( _
    requestContext As RequestContext, _
    pricingDataManager As IPricingDataManagerV2, _
    priceParameters As PriceParameters, _
    rounding As RoundingRule, _
    currencyConverter As CurrencyConverter, _
    itemIds As ISet(Of String), _
    catalogIds As ISet(Of Long), _
    activeDate As DateTimeOffset, _
    priceCalculationMode As PricingCalculationMode, _
    discountCalculationMode As DiscountCalculationMode _
) As PriceContext
'Usage
Dim requestContext As RequestContext
Dim pricingDataManager As IPricingDataManagerV2
Dim priceParameters As PriceParameters
Dim rounding As RoundingRule
Dim currencyConverter As CurrencyConverter
Dim itemIds As ISet(Of String)
Dim catalogIds As ISet(Of Long)
Dim activeDate As DateTimeOffset
Dim priceCalculationMode As PricingCalculationMode
Dim discountCalculationMode As DiscountCalculationMode
Dim returnValue As PriceContext

returnValue = PriceContextHelper.CreatePriceContext(requestContext, _
    pricingDataManager, priceParameters, _
    rounding, currencyConverter, itemIds, _
    catalogIds, activeDate, priceCalculationMode, _
    discountCalculationMode)
```

``` csharp
public static PriceContext CreatePriceContext(
    RequestContext requestContext,
    IPricingDataManagerV2 pricingDataManager,
    PriceParameters priceParameters,
    RoundingRule rounding,
    CurrencyConverter currencyConverter,
    ISet<string> itemIds,
    ISet<long> catalogIds,
    DateTimeOffset activeDate,
    PricingCalculationMode priceCalculationMode,
    DiscountCalculationMode discountCalculationMode
)
```

``` c++
public:
static PriceContext^ CreatePriceContext(
    RequestContext^ requestContext, 
    IPricingDataManagerV2^ pricingDataManager, 
    PriceParameters^ priceParameters, 
    RoundingRule^ rounding, 
    CurrencyConverter^ currencyConverter, 
    ISet<String^>^ itemIds, 
    ISet<long long>^ catalogIds, 
    DateTimeOffset activeDate, 
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

  - priceParameters  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceParameters](priceparameters-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - rounding  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.RoundingRule](roundingrule-delegate-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - currencyConverter  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.CurrencyConverter](currencyconverter-delegate-microsoft-dynamics-commerce-runtime-data.md)  

<!-- end list -->

  - itemIds  
    Type: [System.Collections.Generic.ISet](https://technet.microsoft.com/library/dd412081\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

<!-- end list -->

  - catalogIds  
    Type: [System.Collections.Generic.ISet](https://technet.microsoft.com/library/dd412081\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  

<!-- end list -->

  - activeDate  
    Type: [System.DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))  

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

