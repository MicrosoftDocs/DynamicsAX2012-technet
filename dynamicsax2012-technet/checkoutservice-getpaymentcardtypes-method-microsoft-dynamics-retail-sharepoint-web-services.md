---
title: CheckoutService.GetPaymentCardTypes Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services)
TOCTitle: GetPaymentCardTypes Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.CheckoutService.GetPaymentCardTypes
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.web.services.checkoutservice.getpaymentcardtypes(v=AX.60)
ms:contentKeyID: 62206789
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.CheckoutService.GetPaymentCardTypes
dev_langs:
- CSharp
- C++
- VB
---

# GetPaymentCardTypes Method

Gets the payment card types.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<WebInvokeAttribute(ResponseFormat := WebMessageFormat.Json, RequestFormat := WebMessageFormat.Json,  _
    BodyStyle := WebMessageBodyStyle.WrappedRequest)> _
Public Function GetPaymentCardTypes As PaymentCardTypesResponse
'Usage
Dim instance As CheckoutService
Dim returnValue As PaymentCardTypesResponse

returnValue = instance.GetPaymentCardTypes()
```

``` csharp
[WebInvokeAttribute(ResponseFormat = WebMessageFormat.Json, RequestFormat = WebMessageFormat.Json, 
    BodyStyle = WebMessageBodyStyle.WrappedRequest)]
public PaymentCardTypesResponse GetPaymentCardTypes()
```

``` c++
[WebInvokeAttribute(ResponseFormat = WebMessageFormat::Json, RequestFormat = WebMessageFormat::Json, 
    BodyStyle = WebMessageBodyStyle::WrappedRequest)]
public:
virtual PaymentCardTypesResponse^ GetPaymentCardTypes() sealed
```

#### Return Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.PaymentCardTypesResponse](paymentcardtypesresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
The valid card types accepted for payment.  

#### Implements

[ICheckoutService.GetPaymentCardTypes()](icheckoutservice-getpaymentcardtypes-method-microsoft-dynamics-retail-sharepoint-web-services.md)  

## See Also

#### Reference

[CheckoutService Class](checkoutservice-class-microsoft-dynamics-retail-sharepoint-web-services.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services Namespace](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)

