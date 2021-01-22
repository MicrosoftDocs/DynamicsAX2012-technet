---
title: CheckoutService.GetShippingOptionsPerItem Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services)
TOCTitle: GetShippingOptionsPerItem Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.CheckoutService.GetShippingOptionsPerItem
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.checkoutservice.getshippingoptionsperitem(v=AX.60)
ms:contentKeyID: 62204474
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.CheckoutService.GetShippingOptionsPerItem
dev_langs:
- CSharp
- C++
- VB
---

# GetShippingOptionsPerItem Method

Gets the shipping options for each item on the shopping cart.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<WebInvokeAttribute(ResponseFormat := WebMessageFormat.Json, RequestFormat := WebMessageFormat.Json,  _
    BodyStyle := WebMessageBodyStyle.WrappedRequest)> _
Public Function GetShippingOptionsPerItem As ShippingOptionResponse
'Usage
Dim instance As CheckoutService
Dim returnValue As ShippingOptionResponse

returnValue = instance.GetShippingOptionsPerItem()
```

``` csharp
[WebInvokeAttribute(ResponseFormat = WebMessageFormat.Json, RequestFormat = WebMessageFormat.Json, 
    BodyStyle = WebMessageBodyStyle.WrappedRequest)]
public ShippingOptionResponse GetShippingOptionsPerItem()
```

``` c++
[WebInvokeAttribute(ResponseFormat = WebMessageFormat::Json, RequestFormat = WebMessageFormat::Json, 
    BodyStyle = WebMessageBodyStyle::WrappedRequest)]
public:
virtual ShippingOptionResponse^ GetShippingOptionsPerItem() sealed
```

#### Return Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ShippingOptionResponse](shippingoptionresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
The service response containing the available shipping options per item.  

#### Implements

[ICheckoutService.GetShippingOptionsPerItem()](icheckoutservice-getshippingoptionsperitem-method-microsoft-dynamics-retail-sharepoint-web-services.md)  

## See Also

#### Reference

[CheckoutService Class](checkoutservice-class-microsoft-dynamics-retail-sharepoint-web-services.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services Namespace](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)

