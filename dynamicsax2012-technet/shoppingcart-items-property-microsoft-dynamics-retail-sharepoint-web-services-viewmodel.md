---
title: ShoppingCart.Items Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: Items Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ShoppingCart.Items
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.shoppingcart.items(v=AX.60)
ms:contentKeyID: 62207335
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ShoppingCart.Items
dev_langs:
- CSharp
- C++
- VB
---

# Items Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the cart items.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Items As Collection(Of ShoppingCartItem)
    Get
    Private Set
'Usage
Dim instance As ShoppingCart
Dim value As Collection(Of ShoppingCartItem)

value = instance.Items
```

``` csharp
[DataMemberAttribute]
public Collection<ShoppingCartItem> Items { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property Collection<ShoppingCartItem^>^ Items {
    Collection<ShoppingCartItem^>^ get ();
    private: void set (Collection<ShoppingCartItem^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/library/ms132397\(v=ax.60\))\<[ShoppingCartItem](shoppingcartitem-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)\>  
Returns [Collection\<T\>](https://technet.microsoft.com/library/ms132397\(v=ax.60\)).  

## See Also

#### Reference

[ShoppingCart Class](shoppingcart-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

