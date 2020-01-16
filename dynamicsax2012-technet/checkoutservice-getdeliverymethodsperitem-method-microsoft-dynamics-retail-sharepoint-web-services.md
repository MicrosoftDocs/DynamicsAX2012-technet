---
title: CheckoutService.GetDeliveryMethodsPerItem Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services)
TOCTitle: GetDeliveryMethodsPerItem Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.CheckoutService.GetDeliveryMethodsPerItem(System.Collections.Generic.ICollection{Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.SelectedItemShippingOptions})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.checkoutservice.getdeliverymethodsperitem(v=AX.60)
ms:contentKeyID: 62203021
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.CheckoutService.GetDeliveryMethodsPerItem
dev_langs:
- CSharp
- C++
- VB
---

# GetDeliveryMethodsPerItem Method

Gets the delivery methods for the line items.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<WebInvokeAttribute(ResponseFormat := WebMessageFormat.Json, RequestFormat := WebMessageFormat.Json,  _
    BodyStyle := WebMessageBodyStyle.WrappedRequest)> _
Public Function GetDeliveryMethodsPerItem ( _
    shippingOptions As ICollection(Of SelectedItemShippingOptions) _
) As DeliveryMethodsResponse
'Usage
Dim instance As CheckoutService
Dim shippingOptions As ICollection(Of SelectedItemShippingOptions)
Dim returnValue As DeliveryMethodsResponse

returnValue = instance.GetDeliveryMethodsPerItem(shippingOptions)
```

``` csharp
[WebInvokeAttribute(ResponseFormat = WebMessageFormat.Json, RequestFormat = WebMessageFormat.Json, 
    BodyStyle = WebMessageBodyStyle.WrappedRequest)]
public DeliveryMethodsResponse GetDeliveryMethodsPerItem(
    ICollection<SelectedItemShippingOptions> shippingOptions
)
```

``` c++
[WebInvokeAttribute(ResponseFormat = WebMessageFormat::Json, RequestFormat = WebMessageFormat::Json, 
    BodyStyle = WebMessageBodyStyle::WrappedRequest)]
public:
virtual DeliveryMethodsResponse^ GetDeliveryMethodsPerItem(
    ICollection<SelectedItemShippingOptions^>^ shippingOptions
) sealed
```

#### Parameters

  - shippingOptions  
    Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\))\<[SelectedItemShippingOptions](selecteditemshippingoptions-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)\>  

#### Return Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.DeliveryMethodsResponse](deliverymethodsresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
The service response containing the available shipping options.  

#### Implements

[ICheckoutService.GetDeliveryMethodsPerItem(ICollection\<SelectedItemShippingOptions\>)](icheckoutservice-getdeliverymethodsperitem-method-microsoft-dynamics-retail-sharepoint-web-services.md)  

## See Also

#### Reference

[CheckoutService Class](checkoutservice-class-microsoft-dynamics-retail-sharepoint-web-services.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services Namespace](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)

