---
title: StoreProductAvailabilityService.GetListingAvailableQuantities Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services)
TOCTitle: GetListingAvailableQuantities Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.StoreProductAvailabilityService.GetListingAvailableQuantities(System.Collections.Generic.IEnumerable{System.Int64})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.storeproductavailabilityservice.getlistingavailablequantities(v=AX.60)
ms:contentKeyID: 62204801
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.StoreProductAvailabilityService.GetListingAvailableQuantities
dev_langs:
- CSharp
- C++
- VB
---

# GetListingAvailableQuantities Method

Gets the quantities available of the specified listings.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<WebInvokeAttribute(ResponseFormat := WebMessageFormat.Json, RequestFormat := WebMessageFormat.Json,  _
    BodyStyle := WebMessageBodyStyle.WrappedRequest)> _
Public Function GetListingAvailableQuantities ( _
    listingIds As IEnumerable(Of Long) _
) As ListingAvailableQuantityResponse
'Usage
Dim instance As StoreProductAvailabilityService
Dim listingIds As IEnumerable(Of Long)
Dim returnValue As ListingAvailableQuantityResponse

returnValue = instance.GetListingAvailableQuantities(listingIds)
```

``` csharp
[WebInvokeAttribute(ResponseFormat = WebMessageFormat.Json, RequestFormat = WebMessageFormat.Json, 
    BodyStyle = WebMessageBodyStyle.WrappedRequest)]
public ListingAvailableQuantityResponse GetListingAvailableQuantities(
    IEnumerable<long> listingIds
)
```

``` c++
[WebInvokeAttribute(ResponseFormat = WebMessageFormat::Json, RequestFormat = WebMessageFormat::Json, 
    BodyStyle = WebMessageBodyStyle::WrappedRequest)]
public:
virtual ListingAvailableQuantityResponse^ GetListingAvailableQuantities(
    IEnumerable<long long>^ listingIds
) sealed
```

#### Parameters

  - listingIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  

#### Return Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ListingAvailableQuantityResponse](listingavailablequantityresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
Available quantities for the listings inquired.  

#### Implements

[IStoreProductAvailabilityService.GetListingAvailableQuantities(IEnumerable\<Int64\>)](istoreproductavailabilityservice-getlistingavailablequantities-method-microsoft-dynamics-retail-sharepoint-web-services.md)  

## See Also

#### Reference

[StoreProductAvailabilityService Class](storeproductavailabilityservice-class-microsoft-dynamics-retail-sharepoint-web-services.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services Namespace](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)

