---
title: ShoppingCartItem.ItemType Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: ItemType Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ShoppingCartItem.ItemType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.shoppingcartitem.itemtype(v=AX.60)
ms:contentKeyID: 62207213
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ShoppingCartItem.ItemType
dev_langs:
- CSharp
- C++
- VB
---

# ItemType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the value indicating whether the shopping cart item is a kit, kit component or neither.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ItemType As ShoppingCartItemType
    Get
    Set
'Usage
Dim instance As ShoppingCartItem
Dim value As ShoppingCartItemType

value = instance.ItemType

instance.ItemType = value
```

``` csharp
[DataMemberAttribute]
public ShoppingCartItemType ItemType { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property ShoppingCartItemType ItemType {
    ShoppingCartItemType get ();
    void set (ShoppingCartItemType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ShoppingCartItemType](shoppingcartitemtype-enumeration-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
Returns [ShoppingCartItemType](shoppingcartitemtype-enumeration-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md).  

## Remarks

If the item is a kit, then the kit component collection cannot be empty.

The price of a kit component specifies the delta price from the kit price.

## See Also

#### Reference

[ShoppingCartItem Class](shoppingcartitem-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

