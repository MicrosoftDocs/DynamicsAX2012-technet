---
title: PricingService.GetActiveListingPrice Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services)
TOCTitle: GetActiveListingPrice Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.PricingService.GetActiveListingPrice(System.Collections.Generic.IEnumerable{System.Int64})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.pricingservice.getactivelistingprice(v=AX.60)
ms:contentKeyID: 62205922
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.PricingService.GetActiveListingPrice
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
<WebInvokeAttribute(ResponseFormat := WebMessageFormat.Json, RequestFormat := WebMessageFormat.Json,  _
    BodyStyle := WebMessageBodyStyle.WrappedRequest)> _
Public Function GetActiveListingPrice ( _
    listingIds As IEnumerable(Of Long) _
) As ListingPriceResponse
'Usage
Dim instance As PricingService
Dim listingIds As IEnumerable(Of Long)
Dim returnValue As ListingPriceResponse

returnValue = instance.GetActiveListingPrice(listingIds)
```

``` csharp
[WebInvokeAttribute(ResponseFormat = WebMessageFormat.Json, RequestFormat = WebMessageFormat.Json, 
    BodyStyle = WebMessageBodyStyle.WrappedRequest)]
public ListingPriceResponse GetActiveListingPrice(
    IEnumerable<long> listingIds
)
```

``` c++
[WebInvokeAttribute(ResponseFormat = WebMessageFormat::Json, RequestFormat = WebMessageFormat::Json, 
    BodyStyle = WebMessageBodyStyle::WrappedRequest)]
public:
virtual ListingPriceResponse^ GetActiveListingPrice(
    IEnumerable<long long>^ listingIds
) sealed
```

#### Parameters

  - listingIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  

#### Return Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ListingPriceResponse](listingpriceresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
Response containing active listing prices  

#### Implements

[IPricingService.GetActiveListingPrice(IEnumerable\<Int64\>)](ipricingservice-getactivelistingprice-method-microsoft-dynamics-retail-sharepoint-web-services.md)  

## See Also

#### Reference

[PricingService Class](pricingservice-class-microsoft-dynamics-retail-sharepoint-web-services.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services Namespace](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)

