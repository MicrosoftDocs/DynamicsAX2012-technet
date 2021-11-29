---
title: ItemShippingOptions Constructor (String, ShippingOptions) (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: ItemShippingOptions Constructor (String, ShippingOptions)
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ItemShippingOptions.#ctor(System.String,Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ShippingOptions)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.itemshippingoptions.itemshippingoptions(v=AX.60)
ms:contentKeyID: 62204852
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# ItemShippingOptions Constructor (String, ShippingOptions)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [ItemShippingOptions](itemshippingoptions-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md) object.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    lineId As String, _
    shippingOptions As ShippingOptions _
)
'Usage
Dim lineId As String
Dim shippingOptions As ShippingOptions

Dim instance As New ItemShippingOptions(lineId, _
    shippingOptions)
```

``` csharp
public ItemShippingOptions(
    string lineId,
    ShippingOptions shippingOptions
)
```

``` c++
public:
ItemShippingOptions(
    String^ lineId, 
    ShippingOptions^ shippingOptions
)
```

#### Parameters

  - lineId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - shippingOptions  
    Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ShippingOptions](shippingoptions-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  

## See Also

#### Reference

[ItemShippingOptions Class](itemshippingoptions-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[ItemShippingOptions Overload](itemshippingoptions-constructor-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

