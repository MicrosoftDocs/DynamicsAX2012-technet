---
title: ShoppingCartService.GetShoppingCart Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services)
TOCTitle: GetShoppingCart Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ShoppingCartService.GetShoppingCart(System.Boolean,Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ShoppingCartDataLevel)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.shoppingcartservice.getshoppingcart(v=AX.60)
ms:contentKeyID: 62204884
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ShoppingCartService.GetShoppingCart
dev_langs:
- CSharp
- C++
- VB
---

# GetShoppingCart Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the shopping cart associated

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<WebInvokeAttribute(ResponseFormat := WebMessageFormat.Json, RequestFormat := WebMessageFormat.Json,  _
    BodyStyle := WebMessageBodyStyle.WrappedRequest)> _
Public Function GetShoppingCart ( _
    useSecureToken As Boolean, _
    dataLevel As ShoppingCartDataLevel _
) As ShoppingCartResponse
'Usage
Dim instance As ShoppingCartService
Dim useSecureToken As Boolean
Dim dataLevel As ShoppingCartDataLevel
Dim returnValue As ShoppingCartResponse

returnValue = instance.GetShoppingCart(useSecureToken, _
    dataLevel)
```

``` csharp
[WebInvokeAttribute(ResponseFormat = WebMessageFormat.Json, RequestFormat = WebMessageFormat.Json, 
    BodyStyle = WebMessageBodyStyle.WrappedRequest)]
public ShoppingCartResponse GetShoppingCart(
    bool useSecureToken,
    ShoppingCartDataLevel dataLevel
)
```

``` c++
[WebInvokeAttribute(ResponseFormat = WebMessageFormat::Json, RequestFormat = WebMessageFormat::Json, 
    BodyStyle = WebMessageBodyStyle::WrappedRequest)]
public:
virtual ShoppingCartResponse^ GetShoppingCart(
    bool useSecureToken, 
    ShoppingCartDataLevel dataLevel
) sealed
```

#### Parameters

  - useSecureToken  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - dataLevel  
    Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ShoppingCartDataLevel](shoppingcartdatalevel-enumeration-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ShoppingCartResponse](shoppingcartresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
The service response containing the shopping cart.  

#### Implements

[IShoppingCartService.GetShoppingCart(Boolean, ShoppingCartDataLevel)](ishoppingcartservice-getshoppingcart-method-microsoft-dynamics-retail-sharepoint-web-services.md)  

## See Also

#### Reference

[ShoppingCartService Class](shoppingcartservice-class-microsoft-dynamics-retail-sharepoint-web-services.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services Namespace](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)

