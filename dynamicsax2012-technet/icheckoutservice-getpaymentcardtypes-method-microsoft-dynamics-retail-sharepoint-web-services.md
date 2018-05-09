---
title: ICheckoutService.GetPaymentCardTypes Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services)
TOCTitle: GetPaymentCardTypes Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ICheckoutService.GetPaymentCardTypes
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.web.services.icheckoutservice.getpaymentcardtypes(v=AX.60)
ms:contentKeyID: 62201894
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ICheckoutService.GetPaymentCardTypes
dev_langs:
- CSharp
- C++
- VB
---

# GetPaymentCardTypes Method

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<OperationContractAttribute> _
Function GetPaymentCardTypes As PaymentCardTypesResponse
'Usage
Dim instance As ICheckoutService
Dim returnValue As PaymentCardTypesResponse

returnValue = instance.GetPaymentCardTypes()
```

``` csharp
[OperationContractAttribute]
PaymentCardTypesResponse GetPaymentCardTypes()
```

``` c++
[OperationContractAttribute]
PaymentCardTypesResponse^ GetPaymentCardTypes()
```

#### Return Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.PaymentCardTypesResponse](paymentcardtypesresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  

## See Also

#### Reference

[ICheckoutService Interface](icheckoutservice-interface-microsoft-dynamics-retail-sharepoint-web-services.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services Namespace](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)

