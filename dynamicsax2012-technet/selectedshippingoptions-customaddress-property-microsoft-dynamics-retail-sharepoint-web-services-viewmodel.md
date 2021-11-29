---
title: SelectedShippingOptions.CustomAddress Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: CustomAddress Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.SelectedShippingOptions.CustomAddress
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.selectedshippingoptions.customaddress(v=AX.60)
ms:contentKeyID: 62206654
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.SelectedShippingOptions.CustomAddress
dev_langs:
- CSharp
- C++
- VB
---

# CustomAddress Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the custom address

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CustomAddress As Address
    Get
    Friend Set
'Usage
Dim instance As SelectedShippingOptions
Dim value As Address

value = instance.CustomAddress
```

``` csharp
[DataMemberAttribute]
public Address CustomAddress { get; internal set; }
```

``` c++
[DataMemberAttribute]
public:
property Address^ CustomAddress {
    Address^ get ();
    internal: void set (Address^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.Address](address-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
Returns [Address](address-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md).  

## Remarks

This is supposed to be set with the equivalent of a home delivery.

## See Also

#### Reference

[SelectedShippingOptions Class](selectedshippingoptions-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

