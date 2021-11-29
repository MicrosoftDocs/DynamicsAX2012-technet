---
title: PriceContextHelper.GetAffiliationLoyalTierIds Method  (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine)
TOCTitle: GetAffiliationLoyalTierIds Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContextHelper.GetAffiliationLoyalTierIds(Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingengine.pricecontexthelper.getaffiliationloyaltierids(v=AX.60)
ms:contentKeyID: 62212217
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContextHelper.GetAffiliationLoyalTierIds
dev_langs:
- CSharp
- C++
- VB
---

# GetAffiliationLoyalTierIds Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Get list of affiliation or loyalty tier identifiers.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GetAffiliationLoyalTierIds ( _
    transaction As SalesTransaction _
) As IEnumerable(Of AffiliationLoyaltyTier)
'Usage
Dim transaction As SalesTransaction
Dim returnValue As IEnumerable(Of AffiliationLoyaltyTier)

returnValue = PriceContextHelper.GetAffiliationLoyalTierIds(transaction)
```

``` csharp
public static IEnumerable<AffiliationLoyaltyTier> GetAffiliationLoyalTierIds(
    SalesTransaction transaction
)
```

``` c++
public:
static IEnumerable<AffiliationLoyaltyTier^>^ GetAffiliationLoyalTierIds(
    SalesTransaction^ transaction
)
```

#### Parameters

  - transaction  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[AffiliationLoyaltyTier](affiliationloyaltytier-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
List of affiliation or loyalty tier identifiers.  

## See Also

#### Reference

[PriceContextHelper Class](pricecontexthelper-class-microsoft-dynamics-commerce-runtime-services-pricingengine.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)

