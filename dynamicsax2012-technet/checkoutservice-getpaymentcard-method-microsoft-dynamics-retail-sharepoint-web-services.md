---
title: CheckoutService.GetPaymentCard Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services)
TOCTitle: GetPaymentCard Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.CheckoutService.GetPaymentCard
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.checkoutservice.getpaymentcard(v=AX.60)
ms:contentKeyID: 62204688
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.CheckoutService.GetPaymentCard
dev_langs:
- CSharp
- C++
- VB
---

# GetPaymentCard Method

Gets the payment card.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<WebInvokeAttribute(ResponseFormat := WebMessageFormat.Json, RequestFormat := WebMessageFormat.Json,  _
    BodyStyle := WebMessageBodyStyle.WrappedRequest)> _
Public Function GetPaymentCard As PaymentCardResponse
'Usage
Dim instance As CheckoutService
Dim returnValue As PaymentCardResponse

returnValue = instance.GetPaymentCard()
```

``` csharp
[WebInvokeAttribute(ResponseFormat = WebMessageFormat.Json, RequestFormat = WebMessageFormat.Json, 
    BodyStyle = WebMessageBodyStyle.WrappedRequest)]
public PaymentCardResponse GetPaymentCard()
```

``` c++
[WebInvokeAttribute(ResponseFormat = WebMessageFormat::Json, RequestFormat = WebMessageFormat::Json, 
    BodyStyle = WebMessageBodyStyle::WrappedRequest)]
public:
virtual PaymentCardResponse^ GetPaymentCard() sealed
```

#### Return Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.PaymentCardResponse](paymentcardresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
The payment card.  

#### Implements

[ICheckoutService.GetPaymentCard()](icheckoutservice-getpaymentcard-method-microsoft-dynamics-retail-sharepoint-web-services.md)  

## See Also

#### Reference

[CheckoutService Class](checkoutservice-class-microsoft-dynamics-retail-sharepoint-web-services.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services Namespace](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)

