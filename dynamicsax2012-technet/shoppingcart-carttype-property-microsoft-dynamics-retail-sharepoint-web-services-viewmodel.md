---
title: ShoppingCart.CartType Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: CartType Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ShoppingCart.CartType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.shoppingcart.carttype(v=AX.60)
ms:contentKeyID: 62206794
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ShoppingCart.CartType
dev_langs:
- CSharp
- C++
- VB
---

# CartType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the type of the shopping cart (shopping cart, checkout cart, wishList)

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CartType As CartType
    Get
    Set
'Usage
Dim instance As ShoppingCart
Dim value As CartType

value = instance.CartType

instance.CartType = value
```

``` csharp
[DataMemberAttribute]
public CartType CartType { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property CartType CartType {
    CartType get ();
    void set (CartType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.CartType](carttype-enumeration-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
Returns [CartType](carttype-enumeration-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md).  

## See Also

#### Reference

[ShoppingCart Class](shoppingcart-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

