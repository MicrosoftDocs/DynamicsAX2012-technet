---
title: PricingServiceBase.GetActiveListingPriceWithAffiliationsApplied Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: GetActiveListingPriceWithAffiliationsApplied Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.PricingServiceBase.GetActiveListingPriceWithAffiliationsApplied(System.Collections.Generic.IEnumerable{System.Int64},System.Collections.Generic.IEnumerable{System.Int64})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.pricingservicebase.getactivelistingpricewithaffiliationsapplied(v=AX.60)
ms:contentKeyID: 65317367
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.PricingServiceBase.GetActiveListingPriceWithAffiliationsApplied
dev_langs:
- CSharp
- C++
- VB
---

# GetActiveListingPriceWithAffiliationsApplied Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
Public Overridable Function GetActiveListingPriceWithAffiliationsApplied ( _
    listingIds As IEnumerable(Of Long), _
    affiliationLoyaltyTierIds As IEnumerable(Of Long) _
) As ListingPriceResponse
'Usage
Dim instance As PricingServiceBase
Dim listingIds As IEnumerable(Of Long)
Dim affiliationLoyaltyTierIds As IEnumerable(Of Long)
Dim returnValue As ListingPriceResponse

returnValue = instance.GetActiveListingPriceWithAffiliationsApplied(listingIds, _
    affiliationLoyaltyTierIds)
```

``` csharp
public virtual ListingPriceResponse GetActiveListingPriceWithAffiliationsApplied(
    IEnumerable<long> listingIds,
    IEnumerable<long> affiliationLoyaltyTierIds
)
```

``` c++
public:
virtual ListingPriceResponse^ GetActiveListingPriceWithAffiliationsApplied(
    IEnumerable<long long>^ listingIds, 
    IEnumerable<long long>^ affiliationLoyaltyTierIds
)
```

#### Parameters

  - listingIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  

<!-- end list -->

  - affiliationLoyaltyTierIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ListingPriceResponse](listingpriceresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  

#### Implements

[IPricingService.GetActiveListingPriceWithAffiliationsApplied(IEnumerable\<Int64\>, IEnumerable\<Int64\>)](ipricingservice-getactivelistingpricewithaffiliationsapplied-method-microsoft-dynamics-retail-ecommerce-sdk-services.md)  

## See Also

#### Reference

[PricingServiceBase Class](pricingservicebase-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

