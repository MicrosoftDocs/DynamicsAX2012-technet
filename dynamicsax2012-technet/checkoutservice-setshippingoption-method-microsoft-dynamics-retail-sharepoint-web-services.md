---
title: CheckoutService.SetShippingOption Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services)
TOCTitle: SetShippingOption Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.CheckoutService.SetShippingOption(Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.SelectedOrderShippingOptions)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.checkoutservice.setshippingoption(v=AX.60)
ms:contentKeyID: 62202040
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.CheckoutService.SetShippingOption
dev_langs:
- CSharp
- C++
- VB
---

# SetShippingOption Method

Sets the shipping option for the whole shopping cart.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<WebInvokeAttribute(ResponseFormat := WebMessageFormat.Json, RequestFormat := WebMessageFormat.Json,  _
    BodyStyle := WebMessageBodyStyle.WrappedRequest)> _
Public Function SetShippingOption ( _
    shippingOptions As SelectedOrderShippingOptions _
) As ShoppingCartResponse
'Usage
Dim instance As CheckoutService
Dim shippingOptions As SelectedOrderShippingOptions
Dim returnValue As ShoppingCartResponse

returnValue = instance.SetShippingOption(shippingOptions)
```

``` csharp
[WebInvokeAttribute(ResponseFormat = WebMessageFormat.Json, RequestFormat = WebMessageFormat.Json, 
    BodyStyle = WebMessageBodyStyle.WrappedRequest)]
public ShoppingCartResponse SetShippingOption(
    SelectedOrderShippingOptions shippingOptions
)
```

``` c++
[WebInvokeAttribute(ResponseFormat = WebMessageFormat::Json, RequestFormat = WebMessageFormat::Json, 
    BodyStyle = WebMessageBodyStyle::WrappedRequest)]
public:
virtual ShoppingCartResponse^ SetShippingOption(
    SelectedOrderShippingOptions^ shippingOptions
) sealed
```

#### Parameters

  - shippingOptions  
    Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.SelectedOrderShippingOptions](selectedordershippingoptions-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ShoppingCartResponse](shoppingcartresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
NullResponse object to indicate successful call.  

#### Implements

[ICheckoutService.SetShippingOption(SelectedOrderShippingOptions)](icheckoutservice-setshippingoption-method-microsoft-dynamics-retail-sharepoint-web-services.md)  

## See Also

#### Reference

[CheckoutService Class](checkoutservice-class-microsoft-dynamics-retail-sharepoint-web-services.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services Namespace](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)

