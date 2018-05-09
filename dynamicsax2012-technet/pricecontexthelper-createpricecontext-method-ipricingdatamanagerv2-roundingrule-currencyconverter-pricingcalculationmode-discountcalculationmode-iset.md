---
title: PriceContextHelper.CreatePriceContext Method (IPricingDataManagerV2, RoundingRule, CurrencyConverter, PricingCalculationMode, DiscountCalculationMode, ISet(String), ISet(Int64), IEnumerable(AffiliationLoyaltyTier), String, String, Boolean, String, DateTimeOffset) (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine)
TOCTitle: CreatePriceContext Method (IPricingDataManagerV2, RoundingRule, CurrencyConverter, PricingCalculationMode, DiscountCalculationMode, ISet(String), ISet(Int64), IEnumerable(AffiliationLoyaltyTier), String, String, Boolean, String, DateTimeOffset)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContextHelper.CreatePriceContext(Microsoft.Dynamics.Commerce.Runtime.Data.IPricingDataManagerV2,Microsoft.Dynamics.Commerce.Runtime.DataModel.RoundingRule,Microsoft.Dynamics.Commerce.Runtime.Data.CurrencyConverter,Microsoft.Dynamics.Commerce.Runtime.DataModel.PricingCalculationMode,Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountCalculationMode,System.Collections.Generic.ISet{System.String},System.Collections.Generic.ISet{System.Int64},System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.AffiliationLoyaltyTier},System.String,System.String,System.Boolean,System.String,System.DateTimeOffset)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.pricingengine.pricecontexthelper.createpricecontext(v=AX.60)
ms:contentKeyID: 65322441
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# CreatePriceContext Method (IPricingDataManagerV2, RoundingRule, CurrencyConverter, PricingCalculationMode, DiscountCalculationMode, ISet(String), ISet(Int64), IEnumerable(AffiliationLoyaltyTier), String, String, Boolean, String, DateTimeOffset)

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Public Shared Function CreatePriceContext ( _
    pricingDataManager As IPricingDataManagerV2, _
    rounding As RoundingRule, _
    currencyConverter As CurrencyConverter, _
    priceCalculationMode As PricingCalculationMode, _
    discountCalculationMode As DiscountCalculationMode, _
    itemIds As ISet(Of String), _
    catalogIds As ISet(Of Long), _
    affiliationLoyaltyTiers As IEnumerable(Of AffiliationLoyaltyTier), _
    customerId As String, _
    customerPriceGroup As String, _
    priceIncludesTax As Boolean, _
    currencyCode As String, _
    activeDate As DateTimeOffset _
) As PriceContext
'Usage
Dim pricingDataManager As IPricingDataManagerV2
Dim rounding As RoundingRule
Dim currencyConverter As CurrencyConverter
Dim priceCalculationMode As PricingCalculationMode
Dim discountCalculationMode As DiscountCalculationMode
Dim itemIds As ISet(Of String)
Dim catalogIds As ISet(Of Long)
Dim affiliationLoyaltyTiers As IEnumerable(Of AffiliationLoyaltyTier)
Dim customerId As String
Dim customerPriceGroup As String
Dim priceIncludesTax As Boolean
Dim currencyCode As String
Dim activeDate As DateTimeOffset
Dim returnValue As PriceContext

returnValue = PriceContextHelper.CreatePriceContext(pricingDataManager, _
    rounding, currencyConverter, priceCalculationMode, _
    discountCalculationMode, itemIds, _
    catalogIds, affiliationLoyaltyTiers, _
    customerId, customerPriceGroup, _
    priceIncludesTax, currencyCode, _
    activeDate)
```

``` csharp
public static PriceContext CreatePriceContext(
    IPricingDataManagerV2 pricingDataManager,
    RoundingRule rounding,
    CurrencyConverter currencyConverter,
    PricingCalculationMode priceCalculationMode,
    DiscountCalculationMode discountCalculationMode,
    ISet<string> itemIds,
    ISet<long> catalogIds,
    IEnumerable<AffiliationLoyaltyTier> affiliationLoyaltyTiers,
    string customerId,
    string customerPriceGroup,
    bool priceIncludesTax,
    string currencyCode,
    DateTimeOffset activeDate
)
```

``` c++
public:
static PriceContext^ CreatePriceContext(
    IPricingDataManagerV2^ pricingDataManager, 
    RoundingRule^ rounding, 
    CurrencyConverter^ currencyConverter, 
    PricingCalculationMode priceCalculationMode, 
    DiscountCalculationMode discountCalculationMode, 
    ISet<String^>^ itemIds, 
    ISet<long long>^ catalogIds, 
    IEnumerable<AffiliationLoyaltyTier^>^ affiliationLoyaltyTiers, 
    String^ customerId, 
    String^ customerPriceGroup, 
    bool priceIncludesTax, 
    String^ currencyCode, 
    DateTimeOffset activeDate
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

  - priceCalculationMode  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.PricingCalculationMode](pricingcalculationmode-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - discountCalculationMode  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountCalculationMode](discountcalculationmode-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - itemIds  
    Type: [System.Collections.Generic.ISet](https://technet.microsoft.com/en-us/library/dd412081\(v=ax.60\))\<[String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))\>  

<!-- end list -->

  - catalogIds  
    Type: [System.Collections.Generic.ISet](https://technet.microsoft.com/en-us/library/dd412081\(v=ax.60\))\<[Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))\>  

<!-- end list -->

  - affiliationLoyaltyTiers  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[AffiliationLoyaltyTier](affiliationloyaltytier-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

<!-- end list -->

  - customerId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - customerPriceGroup  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - priceIncludesTax  
    Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - currencyCode  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - activeDate  
    Type: [System.DateTimeOffset](https://technet.microsoft.com/en-us/library/bb341783\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContext](pricecontext-class-microsoft-dynamics-commerce-runtime-services-pricingengine.md)  

## See Also

#### Reference

[PriceContextHelper Class](pricecontexthelper-class-microsoft-dynamics-commerce-runtime-services-pricingengine.md)

[CreatePriceContext Overload](pricecontexthelper-createpricecontext-method-microsoft-dynamics-commerce-runtime-services-pricingengine.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)

