---
title: ShoppingCartService.DeleteShoppingCarts Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services)
TOCTitle: DeleteShoppingCarts Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ShoppingCartService.DeleteShoppingCarts(System.Collections.Generic.ICollection{System.String})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.shoppingcartservice.deleteshoppingcarts(v=AX.60)
ms:contentKeyID: 62205111
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ShoppingCartService.DeleteShoppingCarts
dev_langs:
- CSharp
- C++
- VB
---

# DeleteShoppingCarts Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Deletes the shopping carts associated with given identifiers and the current user.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<WebInvokeAttribute(ResponseFormat := WebMessageFormat.Json, RequestFormat := WebMessageFormat.Json,  _
    BodyStyle := WebMessageBodyStyle.WrappedRequest)> _
Public Function DeleteShoppingCarts ( _
    shoppingCartIds As ICollection(Of String) _
) As NullResponse
'Usage
Dim instance As ShoppingCartService
Dim shoppingCartIds As ICollection(Of String)
Dim returnValue As NullResponse

returnValue = instance.DeleteShoppingCarts(shoppingCartIds)
```

``` csharp
[WebInvokeAttribute(ResponseFormat = WebMessageFormat.Json, RequestFormat = WebMessageFormat.Json, 
    BodyStyle = WebMessageBodyStyle.WrappedRequest)]
public NullResponse DeleteShoppingCarts(
    ICollection<string> shoppingCartIds
)
```

``` c++
[WebInvokeAttribute(ResponseFormat = WebMessageFormat::Json, RequestFormat = WebMessageFormat::Json, 
    BodyStyle = WebMessageBodyStyle::WrappedRequest)]
public:
virtual NullResponse^ DeleteShoppingCarts(
    ICollection<String^>^ shoppingCartIds
) sealed
```

#### Parameters

  - shoppingCartIds  
    Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

#### Return Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.NullResponse](nullresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
The service response.  

#### Implements

[IShoppingCartService.DeleteShoppingCarts(ICollection\<String\>)](ishoppingcartservice-deleteshoppingcarts-method-microsoft-dynamics-retail-sharepoint-web-services.md)  

## See Also

#### Reference

[ShoppingCartService Class](shoppingcartservice-class-microsoft-dynamics-retail-sharepoint-web-services.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services Namespace](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)

