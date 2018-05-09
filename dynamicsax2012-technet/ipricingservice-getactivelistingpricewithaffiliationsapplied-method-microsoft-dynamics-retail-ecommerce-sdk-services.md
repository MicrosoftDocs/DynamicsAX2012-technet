---
title: IPricingService.GetActiveListingPriceWithAffiliationsApplied Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: GetActiveListingPriceWithAffiliationsApplied Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.IPricingService.GetActiveListingPriceWithAffiliationsApplied(System.Collections.Generic.IEnumerable{System.Int64},System.Collections.Generic.IEnumerable{System.Int64})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.ecommerce.sdk.services.ipricingservice.getactivelistingpricewithaffiliationsapplied(v=AX.60)
ms:contentKeyID: 65316803
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.IPricingService.GetActiveListingPriceWithAffiliationsApplied
dev_langs:
- CSharp
- C++
- VB
---

# GetActiveListingPriceWithAffiliationsApplied Method

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
<OperationContractAttribute> _
Function GetActiveListingPriceWithAffiliationsApplied ( _
    listingIds As IEnumerable(Of Long), _
    affiliationLoyaltyTierIds As IEnumerable(Of Long) _
) As ListingPriceResponse
'Usage
Dim instance As IPricingService
Dim listingIds As IEnumerable(Of Long)
Dim affiliationLoyaltyTierIds As IEnumerable(Of Long)
Dim returnValue As ListingPriceResponse

returnValue = instance.GetActiveListingPriceWithAffiliationsApplied(listingIds, _
    affiliationLoyaltyTierIds)
```

``` csharp
[OperationContractAttribute]
ListingPriceResponse GetActiveListingPriceWithAffiliationsApplied(
    IEnumerable<long> listingIds,
    IEnumerable<long> affiliationLoyaltyTierIds
)
```

``` c++
[OperationContractAttribute]
ListingPriceResponse^ GetActiveListingPriceWithAffiliationsApplied(
    IEnumerable<long long>^ listingIds, 
    IEnumerable<long long>^ affiliationLoyaltyTierIds
)
```

#### Parameters

  - listingIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))\>  

<!-- end list -->

  - affiliationLoyaltyTierIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))\>  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ListingPriceResponse](listingpriceresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  

## See Also

#### Reference

[IPricingService Interface](ipricingservice-interface-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

