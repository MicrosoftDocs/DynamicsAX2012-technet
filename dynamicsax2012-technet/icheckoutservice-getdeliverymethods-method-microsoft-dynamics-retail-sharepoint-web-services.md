---
title: ICheckoutService.GetDeliveryMethods Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services)
TOCTitle: GetDeliveryMethods Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ICheckoutService.GetDeliveryMethods(Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.SelectedOrderShippingOptions)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.icheckoutservice.getdeliverymethods(v=AX.60)
ms:contentKeyID: 62206633
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ICheckoutService.GetDeliveryMethods
dev_langs:
- CSharp
- C++
- VB
---

# GetDeliveryMethods Method

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<OperationContractAttribute> _
Function GetDeliveryMethods ( _
    shippingOptions As SelectedOrderShippingOptions _
) As DeliveryMethodsResponse
'Usage
Dim instance As ICheckoutService
Dim shippingOptions As SelectedOrderShippingOptions
Dim returnValue As DeliveryMethodsResponse

returnValue = instance.GetDeliveryMethods(shippingOptions)
```

``` csharp
[OperationContractAttribute]
DeliveryMethodsResponse GetDeliveryMethods(
    SelectedOrderShippingOptions shippingOptions
)
```

``` c++
[OperationContractAttribute]
DeliveryMethodsResponse^ GetDeliveryMethods(
    SelectedOrderShippingOptions^ shippingOptions
)
```

#### Parameters

  - shippingOptions  
    Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.SelectedOrderShippingOptions](selectedordershippingoptions-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.DeliveryMethodsResponse](deliverymethodsresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  

## See Also

#### Reference

[ICheckoutService Interface](icheckoutservice-interface-microsoft-dynamics-retail-sharepoint-web-services.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services Namespace](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)

