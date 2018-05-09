---
title: ICheckoutService.GetDeliveryMethodsPerItem Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services)
TOCTitle: GetDeliveryMethodsPerItem Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ICheckoutService.GetDeliveryMethodsPerItem(System.Collections.Generic.ICollection{Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.SelectedItemShippingOptions})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.web.services.icheckoutservice.getdeliverymethodsperitem(v=AX.60)
ms:contentKeyID: 62202435
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ICheckoutService.GetDeliveryMethodsPerItem
dev_langs:
- CSharp
- C++
- VB
---

# GetDeliveryMethodsPerItem Method

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<OperationContractAttribute> _
Function GetDeliveryMethodsPerItem ( _
    shippingOptions As ICollection(Of SelectedItemShippingOptions) _
) As DeliveryMethodsResponse
'Usage
Dim instance As ICheckoutService
Dim shippingOptions As ICollection(Of SelectedItemShippingOptions)
Dim returnValue As DeliveryMethodsResponse

returnValue = instance.GetDeliveryMethodsPerItem(shippingOptions)
```

``` csharp
[OperationContractAttribute]
DeliveryMethodsResponse GetDeliveryMethodsPerItem(
    ICollection<SelectedItemShippingOptions> shippingOptions
)
```

``` c++
[OperationContractAttribute]
DeliveryMethodsResponse^ GetDeliveryMethodsPerItem(
    ICollection<SelectedItemShippingOptions^>^ shippingOptions
)
```

#### Parameters

  - shippingOptions  
    Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/en-us/library/92t2ye13\(v=ax.60\))\<[SelectedItemShippingOptions](selecteditemshippingoptions-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)\>  

#### Return Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.DeliveryMethodsResponse](deliverymethodsresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  

## See Also

#### Reference

[ICheckoutService Interface](icheckoutservice-interface-microsoft-dynamics-retail-sharepoint-web-services.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services Namespace](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)

