---
title: WishListService.GetWishListsForCurrentCustomer Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services)
TOCTitle: GetWishListsForCurrentCustomer Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.WishListService.GetWishListsForCurrentCustomer
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.wishlistservice.getwishlistsforcurrentcustomer(v=AX.60)
ms:contentKeyID: 62205612
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.WishListService.GetWishListsForCurrentCustomer
dev_langs:
- CSharp
- C++
- VB
---

# GetWishListsForCurrentCustomer Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the wish lists corresponding to customer.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<WebInvokeAttribute(ResponseFormat := WebMessageFormat.Json, RequestFormat := WebMessageFormat.Json,  _
    BodyStyle := WebMessageBodyStyle.WrappedRequest)> _
Public Function GetWishListsForCurrentCustomer As WishListCollectionResponse
'Usage
Dim instance As WishListService
Dim returnValue As WishListCollectionResponse

returnValue = instance.GetWishListsForCurrentCustomer()
```

``` csharp
[WebInvokeAttribute(ResponseFormat = WebMessageFormat.Json, RequestFormat = WebMessageFormat.Json, 
    BodyStyle = WebMessageBodyStyle.WrappedRequest)]
public WishListCollectionResponse GetWishListsForCurrentCustomer()
```

``` c++
[WebInvokeAttribute(ResponseFormat = WebMessageFormat::Json, RequestFormat = WebMessageFormat::Json, 
    BodyStyle = WebMessageBodyStyle::WrappedRequest)]
public:
virtual WishListCollectionResponse^ GetWishListsForCurrentCustomer() sealed
```

#### Return Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.WishListCollectionResponse](wishlistcollectionresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
The service response containing the wish lists.  

#### Implements

[IWishListService.GetWishListsForCurrentCustomer()](iwishlistservice-getwishlistsforcurrentcustomer-method-microsoft-dynamics-retail-sharepoint-web-services.md)  

## See Also

#### Reference

[WishListService Class](wishlistservice-class-microsoft-dynamics-retail-sharepoint-web-services.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services Namespace](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)

