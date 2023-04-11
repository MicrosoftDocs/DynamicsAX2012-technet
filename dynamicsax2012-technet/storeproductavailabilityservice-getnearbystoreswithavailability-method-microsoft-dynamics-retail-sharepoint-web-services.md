---
title: StoreProductAvailabilityService.GetNearbyStoresWithAvailability Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services)
TOCTitle: GetNearbyStoresWithAvailability Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.StoreProductAvailabilityService.GetNearbyStoresWithAvailability(System.Decimal,System.Decimal,System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ShoppingCartItem})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.storeproductavailabilityservice.getnearbystoreswithavailability(v=AX.60)
ms:contentKeyID: 62203836
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.StoreProductAvailabilityService.GetNearbyStoresWithAvailability
dev_langs:
- CSharp
- C++
- VB
---

# GetNearbyStoresWithAvailability Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the nearby stores with availability.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<WebInvokeAttribute(ResponseFormat := WebMessageFormat.Json, RequestFormat := WebMessageFormat.Json,  _
    BodyStyle := WebMessageBodyStyle.WrappedRequest)> _
Public Function GetNearbyStoresWithAvailability ( _
    latitude As Decimal, _
    longitude As Decimal, _
    items As IEnumerable(Of ShoppingCartItem) _
) As StoreProductAvailabilityResponse
'Usage
Dim instance As StoreProductAvailabilityService
Dim latitude As Decimal
Dim longitude As Decimal
Dim items As IEnumerable(Of ShoppingCartItem)
Dim returnValue As StoreProductAvailabilityResponse

returnValue = instance.GetNearbyStoresWithAvailability(latitude, _
    longitude, items)
```

``` csharp
[WebInvokeAttribute(ResponseFormat = WebMessageFormat.Json, RequestFormat = WebMessageFormat.Json, 
    BodyStyle = WebMessageBodyStyle.WrappedRequest)]
public StoreProductAvailabilityResponse GetNearbyStoresWithAvailability(
    decimal latitude,
    decimal longitude,
    IEnumerable<ShoppingCartItem> items
)
```

``` c++
[WebInvokeAttribute(ResponseFormat = WebMessageFormat::Json, RequestFormat = WebMessageFormat::Json, 
    BodyStyle = WebMessageBodyStyle::WrappedRequest)]
public:
virtual StoreProductAvailabilityResponse^ GetNearbyStoresWithAvailability(
    Decimal latitude, 
    Decimal longitude, 
    IEnumerable<ShoppingCartItem^>^ items
) sealed
```

#### Parameters

  - latitude  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - longitude  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - items  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ShoppingCartItem](shoppingcartitem-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)\>  

#### Return Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.StoreProductAvailabilityResponse](storeproductavailabilityresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
Stores with product availability.  

#### Implements

[IStoreProductAvailabilityService.GetNearbyStoresWithAvailability(Decimal, Decimal, IEnumerable\<ShoppingCartItem\>)](istoreproductavailabilityservice-getnearbystoreswithavailability-method-microsoft-dynamics-retail-sharepoint-web-services.md)  

## See Also

#### Reference

[StoreProductAvailabilityService Class](storeproductavailabilityservice-class-microsoft-dynamics-retail-sharepoint-web-services.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services Namespace](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)

