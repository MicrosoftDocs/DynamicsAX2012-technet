---
title: ICheckoutService.GetPaymentCard Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services)
TOCTitle: GetPaymentCard Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ICheckoutService.GetPaymentCard
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.web.services.icheckoutservice.getpaymentcard(v=AX.60)
ms:contentKeyID: 62206013
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ICheckoutService.GetPaymentCard
dev_langs:
- CSharp
- C++
- VB
---

# GetPaymentCard Method

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<OperationContractAttribute> _
Function GetPaymentCard As PaymentCardResponse
'Usage
Dim instance As ICheckoutService
Dim returnValue As PaymentCardResponse

returnValue = instance.GetPaymentCard()
```

``` csharp
[OperationContractAttribute]
PaymentCardResponse GetPaymentCard()
```

``` c++
[OperationContractAttribute]
PaymentCardResponse^ GetPaymentCard()
```

#### Return Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.PaymentCardResponse](paymentcardresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  

## See Also

#### Reference

[ICheckoutService Interface](icheckoutservice-interface-microsoft-dynamics-retail-sharepoint-web-services.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services Namespace](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)

