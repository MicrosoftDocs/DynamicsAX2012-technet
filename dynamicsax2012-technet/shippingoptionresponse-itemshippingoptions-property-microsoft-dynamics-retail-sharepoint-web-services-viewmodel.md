---
title: ShippingOptionResponse.ItemShippingOptions Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: ItemShippingOptions Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ShippingOptionResponse.ItemShippingOptions
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.shippingoptionresponse.itemshippingoptions(v=AX.60)
ms:contentKeyID: 62205027
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ShippingOptionResponse.ItemShippingOptions
dev_langs:
- CSharp
- C++
- VB
---

# ItemShippingOptions Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the shipping options per item.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ItemShippingOptions As Collection(Of ItemShippingOptions)
    Get
    Private Set
'Usage
Dim instance As ShippingOptionResponse
Dim value As Collection(Of ItemShippingOptions)

value = instance.ItemShippingOptions
```

``` csharp
[DataMemberAttribute]
public Collection<ItemShippingOptions> ItemShippingOptions { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property Collection<ItemShippingOptions^>^ ItemShippingOptions {
    Collection<ItemShippingOptions^>^ get ();
    private: void set (Collection<ItemShippingOptions^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/library/ms132397\(v=ax.60\))\<[ItemShippingOptions](itemshippingoptions-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)\>  
Returns [Collection\<T\>](https://technet.microsoft.com/library/ms132397\(v=ax.60\)).  

## See Also

#### Reference

[ShippingOptionResponse Class](shippingoptionresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

