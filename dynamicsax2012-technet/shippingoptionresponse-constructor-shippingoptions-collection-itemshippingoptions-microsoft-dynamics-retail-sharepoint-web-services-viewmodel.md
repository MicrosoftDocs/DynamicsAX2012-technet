---
title: ShippingOptionResponse Constructor (ShippingOptions, Collection(ItemShippingOptions)) (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: ShippingOptionResponse Constructor (ShippingOptions, Collection(ItemShippingOptions))
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ShippingOptionResponse.#ctor(Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ShippingOptions,System.Collections.ObjectModel.Collection{Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ItemShippingOptions})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.shippingoptionresponse.shippingoptionresponse(v=AX.60)
ms:contentKeyID: 62206444
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# ShippingOptionResponse Constructor (ShippingOptions, Collection(ItemShippingOptions))

Initializes a new instance of the [ShippingOptionResponse](shippingoptionresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md) object.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    shippingOptions As ShippingOptions, _
    itemShippingOptions As Collection(Of ItemShippingOptions) _
)
'Usage
Dim shippingOptions As ShippingOptions
Dim itemShippingOptions As Collection(Of ItemShippingOptions)

Dim instance As New ShippingOptionResponse(shippingOptions, _
    itemShippingOptions)
```

``` csharp
public ShippingOptionResponse(
    ShippingOptions shippingOptions,
    Collection<ItemShippingOptions> itemShippingOptions
)
```

``` c++
public:
ShippingOptionResponse(
    ShippingOptions^ shippingOptions, 
    Collection<ItemShippingOptions^>^ itemShippingOptions
)
```

#### Parameters

  - shippingOptions  
    Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ShippingOptions](shippingoptions-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  

<!-- end list -->

  - itemShippingOptions  
    Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/en-us/library/ms132397\(v=ax.60\))\<[ItemShippingOptions](itemshippingoptions-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)\>  

## See Also

#### Reference

[ShippingOptionResponse Class](shippingoptionresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[ShippingOptionResponse Overload](shippingoptionresponse-constructor-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

