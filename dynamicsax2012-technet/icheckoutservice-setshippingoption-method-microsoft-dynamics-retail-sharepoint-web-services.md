---
title: ICheckoutService.SetShippingOption Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services)
TOCTitle: SetShippingOption Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ICheckoutService.SetShippingOption(Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.SelectedOrderShippingOptions)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.icheckoutservice.setshippingoption(v=AX.60)
ms:contentKeyID: 62204493
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ICheckoutService.SetShippingOption
dev_langs:
- CSharp
- C++
- VB
---

# SetShippingOption Method

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<OperationContractAttribute> _
Function SetShippingOption ( _
    shippingOptions As SelectedOrderShippingOptions _
) As ShoppingCartResponse
'Usage
Dim instance As ICheckoutService
Dim shippingOptions As SelectedOrderShippingOptions
Dim returnValue As ShoppingCartResponse

returnValue = instance.SetShippingOption(shippingOptions)
```

``` csharp
[OperationContractAttribute]
ShoppingCartResponse SetShippingOption(
    SelectedOrderShippingOptions shippingOptions
)
```

``` c++
[OperationContractAttribute]
ShoppingCartResponse^ SetShippingOption(
    SelectedOrderShippingOptions^ shippingOptions
)
```

#### Parameters

  - shippingOptions  
    Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.SelectedOrderShippingOptions](selectedordershippingoptions-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ShoppingCartResponse](shoppingcartresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  

## See Also

#### Reference

[ICheckoutService Interface](icheckoutservice-interface-microsoft-dynamics-retail-sharepoint-web-services.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services Namespace](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)

