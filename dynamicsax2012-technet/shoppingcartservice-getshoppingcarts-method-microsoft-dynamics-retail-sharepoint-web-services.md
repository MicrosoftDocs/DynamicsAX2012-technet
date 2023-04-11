---
title: ShoppingCartService.GetShoppingCarts Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services)
TOCTitle: GetShoppingCarts Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ShoppingCartService.GetShoppingCarts(Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ShoppingCartDataLevel)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.shoppingcartservice.getshoppingcarts(v=AX.60)
ms:contentKeyID: 62207214
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ShoppingCartService.GetShoppingCarts
dev_langs:
- CSharp
- C++
- VB
---

# GetShoppingCarts Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets all shopping carts associated with the current user.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<WebInvokeAttribute(ResponseFormat := WebMessageFormat.Json, RequestFormat := WebMessageFormat.Json,  _
    BodyStyle := WebMessageBodyStyle.WrappedRequest)> _
Public Function GetShoppingCarts ( _
    dataLevel As ShoppingCartDataLevel _
) As ShoppingCartCollectionResponse
'Usage
Dim instance As ShoppingCartService
Dim dataLevel As ShoppingCartDataLevel
Dim returnValue As ShoppingCartCollectionResponse

returnValue = instance.GetShoppingCarts(dataLevel)
```

``` csharp
[WebInvokeAttribute(ResponseFormat = WebMessageFormat.Json, RequestFormat = WebMessageFormat.Json, 
    BodyStyle = WebMessageBodyStyle.WrappedRequest)]
public ShoppingCartCollectionResponse GetShoppingCarts(
    ShoppingCartDataLevel dataLevel
)
```

``` c++
[WebInvokeAttribute(ResponseFormat = WebMessageFormat::Json, RequestFormat = WebMessageFormat::Json, 
    BodyStyle = WebMessageBodyStyle::WrappedRequest)]
public:
virtual ShoppingCartCollectionResponse^ GetShoppingCarts(
    ShoppingCartDataLevel dataLevel
) sealed
```

#### Parameters

  - dataLevel  
    Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ShoppingCartDataLevel](shoppingcartdatalevel-enumeration-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ShoppingCartCollectionResponse](shoppingcartcollectionresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
The service response containing the list of shopping carts.  

#### Implements

[IShoppingCartService.GetShoppingCarts(ShoppingCartDataLevel)](ishoppingcartservice-getshoppingcarts-method-microsoft-dynamics-retail-sharepoint-web-services.md)  

## See Also

#### Reference

[ShoppingCartService Class](shoppingcartservice-class-microsoft-dynamics-retail-sharepoint-web-services.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services Namespace](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)

