---
title: ICheckoutService.GetShippingOptionsPerItem Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services)
TOCTitle: GetShippingOptionsPerItem Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ICheckoutService.GetShippingOptionsPerItem
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.web.services.icheckoutservice.getshippingoptionsperitem(v=AX.60)
ms:contentKeyID: 62206171
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ICheckoutService.GetShippingOptionsPerItem
dev_langs:
- CSharp
- C++
- VB
---

# GetShippingOptionsPerItem Method

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<OperationContractAttribute> _
Function GetShippingOptionsPerItem As ShippingOptionResponse
'Usage
Dim instance As ICheckoutService
Dim returnValue As ShippingOptionResponse

returnValue = instance.GetShippingOptionsPerItem()
```

``` csharp
[OperationContractAttribute]
ShippingOptionResponse GetShippingOptionsPerItem()
```

``` c++
[OperationContractAttribute]
ShippingOptionResponse^ GetShippingOptionsPerItem()
```

#### Return Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ShippingOptionResponse](shippingoptionresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  

## See Also

#### Reference

[ICheckoutService Interface](icheckoutservice-interface-microsoft-dynamics-retail-sharepoint-web-services.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services Namespace](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)

