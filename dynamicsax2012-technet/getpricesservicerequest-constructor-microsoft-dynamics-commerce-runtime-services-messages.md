---
title: GetPricesServiceRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetPricesServiceRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetPricesServiceRequest.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine},System.DateTimeOffset,System.String,System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.PricingCalculationMode,System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.AffiliationLoyaltyTier})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.getpricesservicerequest.getpricesservicerequest(v=AX.60)
ms:contentKeyID: 65316282
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetPricesServiceRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetPricesServiceRequest Constructor

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    salesLines As IEnumerable(Of SalesLine), _
    activeDate As DateTimeOffset, _
    customerAccount As String, _
    customerPriceGroup As String, _
    priceCalculationMode As PricingCalculationMode, _
    affiliationLoyaltyTiers As IEnumerable(Of AffiliationLoyaltyTier) _
)
'Usage
Dim salesLines As IEnumerable(Of SalesLine)
Dim activeDate As DateTimeOffset
Dim customerAccount As String
Dim customerPriceGroup As String
Dim priceCalculationMode As PricingCalculationMode
Dim affiliationLoyaltyTiers As IEnumerable(Of AffiliationLoyaltyTier)

Dim instance As New GetPricesServiceRequest(salesLines, _
    activeDate, customerAccount, customerPriceGroup, _
    priceCalculationMode, affiliationLoyaltyTiers)
```

``` csharp
public GetPricesServiceRequest(
    IEnumerable<SalesLine> salesLines,
    DateTimeOffset activeDate,
    string customerAccount,
    string customerPriceGroup,
    PricingCalculationMode priceCalculationMode,
    IEnumerable<AffiliationLoyaltyTier> affiliationLoyaltyTiers
)
```

``` c++
public:
GetPricesServiceRequest(
    IEnumerable<SalesLine^>^ salesLines, 
    DateTimeOffset activeDate, 
    String^ customerAccount, 
    String^ customerPriceGroup, 
    PricingCalculationMode priceCalculationMode, 
    IEnumerable<AffiliationLoyaltyTier^>^ affiliationLoyaltyTiers
)
```

#### Parameters

  - salesLines  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[SalesLine](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

<!-- end list -->

  - activeDate  
    Type: [System.DateTimeOffset](https://technet.microsoft.com/en-us/library/bb341783\(v=ax.60\))  

<!-- end list -->

  - customerAccount  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - customerPriceGroup  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - priceCalculationMode  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.PricingCalculationMode](pricingcalculationmode-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - affiliationLoyaltyTiers  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[AffiliationLoyaltyTier](affiliationloyaltytier-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetPricesServiceRequest Class](getpricesservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

