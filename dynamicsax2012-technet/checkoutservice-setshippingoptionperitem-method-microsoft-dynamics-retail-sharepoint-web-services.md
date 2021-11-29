---
title: CheckoutService.SetShippingOptionPerItem Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services)
TOCTitle: SetShippingOptionPerItem Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.CheckoutService.SetShippingOptionPerItem(System.Collections.Generic.ICollection{Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.SelectedItemShippingOptions})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.checkoutservice.setshippingoptionperitem(v=AX.60)
ms:contentKeyID: 62207408
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.CheckoutService.SetShippingOptionPerItem
dev_langs:
- CSharp
- C++
- VB
---

# SetShippingOptionPerItem Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Sets the shipping options per item.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<WebInvokeAttribute(ResponseFormat := WebMessageFormat.Json, RequestFormat := WebMessageFormat.Json,  _
    BodyStyle := WebMessageBodyStyle.WrappedRequest)> _
Public Function SetShippingOptionPerItem ( _
    shippingOptions As ICollection(Of SelectedItemShippingOptions) _
) As ShoppingCartResponse
'Usage
Dim instance As CheckoutService
Dim shippingOptions As ICollection(Of SelectedItemShippingOptions)
Dim returnValue As ShoppingCartResponse

returnValue = instance.SetShippingOptionPerItem(shippingOptions)
```

``` csharp
[WebInvokeAttribute(ResponseFormat = WebMessageFormat.Json, RequestFormat = WebMessageFormat.Json, 
    BodyStyle = WebMessageBodyStyle.WrappedRequest)]
public ShoppingCartResponse SetShippingOptionPerItem(
    ICollection<SelectedItemShippingOptions> shippingOptions
)
```

``` c++
[WebInvokeAttribute(ResponseFormat = WebMessageFormat::Json, RequestFormat = WebMessageFormat::Json, 
    BodyStyle = WebMessageBodyStyle::WrappedRequest)]
public:
virtual ShoppingCartResponse^ SetShippingOptionPerItem(
    ICollection<SelectedItemShippingOptions^>^ shippingOptions
) sealed
```

#### Parameters

  - shippingOptions  
    Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\))\<[SelectedItemShippingOptions](selecteditemshippingoptions-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)\>  

#### Return Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ShoppingCartResponse](shoppingcartresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
NullResponse object to indicate successful call.  

#### Implements

[ICheckoutService.SetShippingOptionPerItem(ICollection\<SelectedItemShippingOptions\>)](icheckoutservice-setshippingoptionperitem-method-microsoft-dynamics-retail-sharepoint-web-services.md)  

## See Also

#### Reference

[CheckoutService Class](checkoutservice-class-microsoft-dynamics-retail-sharepoint-web-services.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services Namespace](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)

