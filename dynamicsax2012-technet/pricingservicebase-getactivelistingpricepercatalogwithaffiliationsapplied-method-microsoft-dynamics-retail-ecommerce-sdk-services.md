---
title: PricingServiceBase.GetActiveListingPricePerCatalogWithAffiliationsApplied Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: GetActiveListingPricePerCatalogWithAffiliationsApplied Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.PricingServiceBase.GetActiveListingPricePerCatalogWithAffiliationsApplied(System.Collections.Generic.IEnumerable{System.Int64},System.Int64,System.Int64,System.Collections.Generic.IEnumerable{System.Int64})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.pricingservicebase.getactivelistingpricepercatalogwithaffiliationsapplied(v=AX.60)
ms:contentKeyID: 65318095
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.PricingServiceBase.GetActiveListingPricePerCatalogWithAffiliationsApplied
dev_langs:
- CSharp
- C++
- VB
---

# GetActiveListingPricePerCatalogWithAffiliationsApplied Method

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
Public Overridable Function GetActiveListingPricePerCatalogWithAffiliationsApplied ( _
    listingIds As IEnumerable(Of Long), _
    channelId As Long, _
    catalogId As Long, _
    affiliationLoyaltyTierIds As IEnumerable(Of Long) _
) As ListingPriceResponse
'Usage
Dim instance As PricingServiceBase
Dim listingIds As IEnumerable(Of Long)
Dim channelId As Long
Dim catalogId As Long
Dim affiliationLoyaltyTierIds As IEnumerable(Of Long)
Dim returnValue As ListingPriceResponse

returnValue = instance.GetActiveListingPricePerCatalogWithAffiliationsApplied(listingIds, _
    channelId, catalogId, affiliationLoyaltyTierIds)
```

``` csharp
public virtual ListingPriceResponse GetActiveListingPricePerCatalogWithAffiliationsApplied(
    IEnumerable<long> listingIds,
    long channelId,
    long catalogId,
    IEnumerable<long> affiliationLoyaltyTierIds
)
```

``` c++
public:
virtual ListingPriceResponse^ GetActiveListingPricePerCatalogWithAffiliationsApplied(
    IEnumerable<long long>^ listingIds, 
    long long channelId, 
    long long catalogId, 
    IEnumerable<long long>^ affiliationLoyaltyTierIds
)
```

#### Parameters

  - listingIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  

<!-- end list -->

  - channelId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - catalogId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - affiliationLoyaltyTierIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ListingPriceResponse](listingpriceresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  

#### Implements

[IPricingService.GetActiveListingPricePerCatalogWithAffiliationsApplied(IEnumerable\<Int64\>, Int64, Int64, IEnumerable\<Int64\>)](ipricingservice-getactivelistingpricepercatalogwithaffiliationsapplied-method-microsoft-dynamics-retail-ecommerce-sdk-services.md)  

## See Also

#### Reference

[PricingServiceBase Class](pricingservicebase-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

