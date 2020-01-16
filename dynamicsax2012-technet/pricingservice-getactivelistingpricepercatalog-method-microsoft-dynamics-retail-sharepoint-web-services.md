---
title: PricingService.GetActiveListingPricePerCatalog Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services)
TOCTitle: GetActiveListingPricePerCatalog Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.PricingService.GetActiveListingPricePerCatalog(System.Collections.Generic.IEnumerable{System.Int64},System.Int64,System.Int64)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.pricingservice.getactivelistingpricepercatalog(v=AX.60)
ms:contentKeyID: 62205280
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.PricingService.GetActiveListingPricePerCatalog
dev_langs:
- CSharp
- C++
- VB
---

# GetActiveListingPricePerCatalog Method

Gets listing price of an item for the give channel and catalog.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<WebInvokeAttribute(ResponseFormat := WebMessageFormat.Json, RequestFormat := WebMessageFormat.Json,  _
    BodyStyle := WebMessageBodyStyle.WrappedRequest)> _
Public Function GetActiveListingPricePerCatalog ( _
    listingIds As IEnumerable(Of Long), _
    channelId As Long, _
    catalogId As Long _
) As ListingPriceResponse
'Usage
Dim instance As PricingService
Dim listingIds As IEnumerable(Of Long)
Dim channelId As Long
Dim catalogId As Long
Dim returnValue As ListingPriceResponse

returnValue = instance.GetActiveListingPricePerCatalog(listingIds, _
    channelId, catalogId)
```

``` csharp
[WebInvokeAttribute(ResponseFormat = WebMessageFormat.Json, RequestFormat = WebMessageFormat.Json, 
    BodyStyle = WebMessageBodyStyle.WrappedRequest)]
public ListingPriceResponse GetActiveListingPricePerCatalog(
    IEnumerable<long> listingIds,
    long channelId,
    long catalogId
)
```

``` c++
[WebInvokeAttribute(ResponseFormat = WebMessageFormat::Json, RequestFormat = WebMessageFormat::Json, 
    BodyStyle = WebMessageBodyStyle::WrappedRequest)]
public:
virtual ListingPriceResponse^ GetActiveListingPricePerCatalog(
    IEnumerable<long long>^ listingIds, 
    long long channelId, 
    long long catalogId
) sealed
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

#### Return Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ListingPriceResponse](listingpriceresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
Response containing active listing prices  

#### Implements

[IPricingService.GetActiveListingPricePerCatalog(IEnumerable\<Int64\>, Int64, Int64)](ipricingservice-getactivelistingpricepercatalog-method-microsoft-dynamics-retail-sharepoint-web-services.md)  

## See Also

#### Reference

[PricingService Class](pricingservice-class-microsoft-dynamics-retail-sharepoint-web-services.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services Namespace](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)

