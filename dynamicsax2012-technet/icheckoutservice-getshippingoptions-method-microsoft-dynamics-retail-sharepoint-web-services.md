---
title: ICheckoutService.GetShippingOptions Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services)
TOCTitle: GetShippingOptions Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ICheckoutService.GetShippingOptions
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.icheckoutservice.getshippingoptions(v=AX.60)
ms:contentKeyID: 62203905
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ICheckoutService.GetShippingOptions
dev_langs:
- CSharp
- C++
- VB
---

# GetShippingOptions Method

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<OperationContractAttribute> _
Function GetShippingOptions As ShippingOptionResponse
'Usage
Dim instance As ICheckoutService
Dim returnValue As ShippingOptionResponse

returnValue = instance.GetShippingOptions()
```

``` csharp
[OperationContractAttribute]
ShippingOptionResponse GetShippingOptions()
```

``` c++
[OperationContractAttribute]
ShippingOptionResponse^ GetShippingOptions()
```

#### Return Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ShippingOptionResponse](shippingoptionresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  

## See Also

#### Reference

[ICheckoutService Interface](icheckoutservice-interface-microsoft-dynamics-retail-sharepoint-web-services.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services Namespace](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)

