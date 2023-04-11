---
title: ShoppingCartService.SaveShoppingCart Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services)
TOCTitle: SaveShoppingCart Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ShoppingCartService.SaveShoppingCart(System.Boolean,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.shoppingcartservice.saveshoppingcart(v=AX.60)
ms:contentKeyID: 62203896
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ShoppingCartService.SaveShoppingCart
dev_langs:
- CSharp
- C++
- VB
---

# SaveShoppingCart Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Saves the name of the shopping cart associated with the given identifier.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<WebInvokeAttribute(ResponseFormat := WebMessageFormat.Json, RequestFormat := WebMessageFormat.Json,  _
    BodyStyle := WebMessageBodyStyle.WrappedRequest)> _
Public Function SaveShoppingCart ( _
    useSecureToken As Boolean, _
    name As String _
) As NullResponse
'Usage
Dim instance As ShoppingCartService
Dim useSecureToken As Boolean
Dim name As String
Dim returnValue As NullResponse

returnValue = instance.SaveShoppingCart(useSecureToken, _
    name)
```

``` csharp
[WebInvokeAttribute(ResponseFormat = WebMessageFormat.Json, RequestFormat = WebMessageFormat.Json, 
    BodyStyle = WebMessageBodyStyle.WrappedRequest)]
public NullResponse SaveShoppingCart(
    bool useSecureToken,
    string name
)
```

``` c++
[WebInvokeAttribute(ResponseFormat = WebMessageFormat::Json, RequestFormat = WebMessageFormat::Json, 
    BodyStyle = WebMessageBodyStyle::WrappedRequest)]
public:
virtual NullResponse^ SaveShoppingCart(
    bool useSecureToken, 
    String^ name
) sealed
```

#### Parameters

  - useSecureToken  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - name  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.NullResponse](nullresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
The service response.  

#### Implements

[IShoppingCartService.SaveShoppingCart(Boolean, String)](ishoppingcartservice-saveshoppingcart-method-microsoft-dynamics-retail-sharepoint-web-services.md)  

## See Also

#### Reference

[ShoppingCartService Class](shoppingcartservice-class-microsoft-dynamics-retail-sharepoint-web-services.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services Namespace](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)

