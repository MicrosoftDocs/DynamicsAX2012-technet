---
title: ICheckoutService.GetAllDeliveryMethods Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services)
TOCTitle: GetAllDeliveryMethods Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ICheckoutService.GetAllDeliveryMethods
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.icheckoutservice.getalldeliverymethods(v=AX.60)
ms:contentKeyID: 62204865
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ICheckoutService.GetAllDeliveryMethods
dev_langs:
- CSharp
- C++
- VB
---

# GetAllDeliveryMethods Method

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<OperationContractAttribute> _
Function GetAllDeliveryMethods As DeliveryMethodsResponse
'Usage
Dim instance As ICheckoutService
Dim returnValue As DeliveryMethodsResponse

returnValue = instance.GetAllDeliveryMethods()
```

``` csharp
[OperationContractAttribute]
DeliveryMethodsResponse GetAllDeliveryMethods()
```

``` c++
[OperationContractAttribute]
DeliveryMethodsResponse^ GetAllDeliveryMethods()
```

#### Return Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.DeliveryMethodsResponse](deliverymethodsresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  

## See Also

#### Reference

[ICheckoutService Interface](icheckoutservice-interface-microsoft-dynamics-retail-sharepoint-web-services.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services Namespace](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)

