---
title: CheckoutService.GetDeliveryMethods Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services)
TOCTitle: GetDeliveryMethods Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.CheckoutService.GetDeliveryMethods(Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.SelectedOrderShippingOptions)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.checkoutservice.getdeliverymethods(v=AX.60)
ms:contentKeyID: 62204069
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.CheckoutService.GetDeliveryMethods
dev_langs:
- CSharp
- C++
- VB
---

# GetDeliveryMethods Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the delivery methods for the order.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<WebInvokeAttribute(ResponseFormat := WebMessageFormat.Json, RequestFormat := WebMessageFormat.Json,  _
    BodyStyle := WebMessageBodyStyle.WrappedRequest)> _
Public Function GetDeliveryMethods ( _
    shippingOptions As SelectedOrderShippingOptions _
) As DeliveryMethodsResponse
'Usage
Dim instance As CheckoutService
Dim shippingOptions As SelectedOrderShippingOptions
Dim returnValue As DeliveryMethodsResponse

returnValue = instance.GetDeliveryMethods(shippingOptions)
```

``` csharp
[WebInvokeAttribute(ResponseFormat = WebMessageFormat.Json, RequestFormat = WebMessageFormat.Json, 
    BodyStyle = WebMessageBodyStyle.WrappedRequest)]
public DeliveryMethodsResponse GetDeliveryMethods(
    SelectedOrderShippingOptions shippingOptions
)
```

``` c++
[WebInvokeAttribute(ResponseFormat = WebMessageFormat::Json, RequestFormat = WebMessageFormat::Json, 
    BodyStyle = WebMessageBodyStyle::WrappedRequest)]
public:
virtual DeliveryMethodsResponse^ GetDeliveryMethods(
    SelectedOrderShippingOptions^ shippingOptions
) sealed
```

#### Parameters

  - shippingOptions  
    Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.SelectedOrderShippingOptions](selectedordershippingoptions-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.DeliveryMethodsResponse](deliverymethodsresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
The service response containing the available shipping options.  

#### Implements

[ICheckoutService.GetDeliveryMethods(SelectedOrderShippingOptions)](icheckoutservice-getdeliverymethods-method-microsoft-dynamics-retail-sharepoint-web-services.md)  

## See Also

#### Reference

[CheckoutService Class](checkoutservice-class-microsoft-dynamics-retail-sharepoint-web-services.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services Namespace](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)

