---
title: ItemShippingOptions.ShippingOptions Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: ShippingOptions Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ItemShippingOptions.ShippingOptions
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.itemshippingoptions.shippingoptions(v=AX.60)
ms:contentKeyID: 62207005
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ItemShippingOptions.ShippingOptions
dev_langs:
- CSharp
- C++
- VB
---

# ShippingOptions Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the shipping options.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ShippingOptions As ShippingOptions
    Get
    Private Set
'Usage
Dim instance As ItemShippingOptions
Dim value As ShippingOptions

value = instance.ShippingOptions
```

``` csharp
[DataMemberAttribute]
public ShippingOptions ShippingOptions { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ShippingOptions^ ShippingOptions {
    ShippingOptions^ get ();
    private: void set (ShippingOptions^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ShippingOptions](shippingoptions-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
Returns [ShippingOptions](shippingoptions-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md).  

## See Also

#### Reference

[ItemShippingOptions Class](itemshippingoptions-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

