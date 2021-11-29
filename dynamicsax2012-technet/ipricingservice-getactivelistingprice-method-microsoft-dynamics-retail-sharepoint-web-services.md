---
title: IPricingService.GetActiveListingPrice Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services)
TOCTitle: GetActiveListingPrice Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.IPricingService.GetActiveListingPrice(System.Collections.Generic.IEnumerable{System.Int64})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.ipricingservice.getactivelistingprice(v=AX.60)
ms:contentKeyID: 62204161
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.IPricingService.GetActiveListingPrice
dev_langs:
- CSharp
- C++
- VB
---

# GetActiveListingPrice Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the best price for an item between all active catalogs for the current channel.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<OperationContractAttribute> _
Function GetActiveListingPrice ( _
    listingIds As IEnumerable(Of Long) _
) As ListingPriceResponse
'Usage
Dim instance As IPricingService
Dim listingIds As IEnumerable(Of Long)
Dim returnValue As ListingPriceResponse

returnValue = instance.GetActiveListingPrice(listingIds)
```

``` csharp
[OperationContractAttribute]
ListingPriceResponse GetActiveListingPrice(
    IEnumerable<long> listingIds
)
```

``` c++
[OperationContractAttribute]
ListingPriceResponse^ GetActiveListingPrice(
    IEnumerable<long long>^ listingIds
)
```

#### Parameters

  - listingIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  

#### Return Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ListingPriceResponse](listingpriceresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
Response containing active listing prices  

## See Also

#### Reference

[IPricingService Interface](ipricingservice-interface-microsoft-dynamics-retail-sharepoint-web-services.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services Namespace](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)

