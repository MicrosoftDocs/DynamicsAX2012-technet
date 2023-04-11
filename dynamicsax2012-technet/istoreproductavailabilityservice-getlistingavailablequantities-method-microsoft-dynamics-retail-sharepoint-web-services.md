---
title: IStoreProductAvailabilityService.GetListingAvailableQuantities Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services)
TOCTitle: GetListingAvailableQuantities Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.IStoreProductAvailabilityService.GetListingAvailableQuantities(System.Collections.Generic.IEnumerable{System.Int64})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.istoreproductavailabilityservice.getlistingavailablequantities(v=AX.60)
ms:contentKeyID: 62206843
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.IStoreProductAvailabilityService.GetListingAvailableQuantities
dev_langs:
- CSharp
- C++
- VB
---

# GetListingAvailableQuantities Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the quantities available of the specified listings.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<OperationContractAttribute> _
Function GetListingAvailableQuantities ( _
    listingIds As IEnumerable(Of Long) _
) As ListingAvailableQuantityResponse
'Usage
Dim instance As IStoreProductAvailabilityService
Dim listingIds As IEnumerable(Of Long)
Dim returnValue As ListingAvailableQuantityResponse

returnValue = instance.GetListingAvailableQuantities(listingIds)
```

``` csharp
[OperationContractAttribute]
ListingAvailableQuantityResponse GetListingAvailableQuantities(
    IEnumerable<long> listingIds
)
```

``` c++
[OperationContractAttribute]
ListingAvailableQuantityResponse^ GetListingAvailableQuantities(
    IEnumerable<long long>^ listingIds
)
```

#### Parameters

  - listingIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  

#### Return Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ListingAvailableQuantityResponse](listingavailablequantityresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
Available quantities for the listings inquired.  

## See Also

#### Reference

[IStoreProductAvailabilityService Interface](istoreproductavailabilityservice-interface-microsoft-dynamics-retail-sharepoint-web-services.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services Namespace](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)

