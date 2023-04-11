---
title: ShoppingCartItem.KitComponents Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: KitComponents Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ShoppingCartItem.KitComponents
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.shoppingcartitem.kitcomponents(v=AX.60)
ms:contentKeyID: 62203173
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ShoppingCartItem.KitComponents
dev_langs:
- CSharp
- C++
- VB
---

# KitComponents Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets kit components.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property KitComponents As Collection(Of ShoppingCartItem)
    Get
    Set
'Usage
Dim instance As ShoppingCartItem
Dim value As Collection(Of ShoppingCartItem)

value = instance.KitComponents

instance.KitComponents = value
```

``` csharp
[DataMemberAttribute]
public Collection<ShoppingCartItem> KitComponents { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Collection<ShoppingCartItem^>^ KitComponents {
    Collection<ShoppingCartItem^>^ get ();
    void set (Collection<ShoppingCartItem^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/library/ms132397\(v=ax.60\))\<[ShoppingCartItem](shoppingcartitem-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)\>  
Returns [Collection\<T\>](https://technet.microsoft.com/library/ms132397\(v=ax.60\)).  

## See Also

#### Reference

[ShoppingCartItem Class](shoppingcartitem-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

