---
title: ShippingOptionResponse.OrderShippingOptions Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: OrderShippingOptions Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ShippingOptionResponse.OrderShippingOptions
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.shippingoptionresponse.ordershippingoptions(v=AX.60)
ms:contentKeyID: 62202290
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ShippingOptionResponse.OrderShippingOptions
dev_langs:
- CSharp
- C++
- VB
---

# OrderShippingOptions Property

Gets or sets the shipping options.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property OrderShippingOptions As ShippingOptions
    Get
    Friend Set
'Usage
Dim instance As ShippingOptionResponse
Dim value As ShippingOptions

value = instance.OrderShippingOptions
```

``` csharp
[DataMemberAttribute]
public ShippingOptions OrderShippingOptions { get; internal set; }
```

``` c++
[DataMemberAttribute]
public:
property ShippingOptions^ OrderShippingOptions {
    ShippingOptions^ get ();
    internal: void set (ShippingOptions^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ShippingOptions](shippingoptions-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
Returns [ShippingOptions](shippingoptions-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md).  

## See Also

#### Reference

[ShippingOptionResponse Class](shippingoptionresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

