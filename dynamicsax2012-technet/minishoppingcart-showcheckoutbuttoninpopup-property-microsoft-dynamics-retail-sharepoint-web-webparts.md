---
title: MiniShoppingCart.ShowCheckoutButtonInPopup Property  (Microsoft.Dynamics.Retail.SharePoint.Web.WebParts)
TOCTitle: ShowCheckoutButtonInPopup Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.MiniShoppingCart.ShowCheckoutButtonInPopup
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.webparts.minishoppingcart.showcheckoutbuttoninpopup(v=AX.60)
ms:contentKeyID: 62203248
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.MiniShoppingCart.ShowCheckoutButtonInPopup
dev_langs:
- CSharp
- C++
- VB
---

# ShowCheckoutButtonInPopup Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets whether to show the Shopping Cart LInk in the Popup.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.WebParts](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.WebParts (in Microsoft.Dynamics.Retail.SP.Web.WebParts.dll)

## Syntax

``` vb
'Declaration
<PersonalizableAttribute(PersonalizationScope.Shared)> _
<LocalizedWebDisplayNameAttribute("MiniShoppingCartWebDisplayNameShowCheckoutButtonInPopup")> _
<WebBrowsableAttribute(True)> _
<WebPartStorageAttribute(Storage.Shared)> _
<LocalizedWebDescriptionAttribute("MiniShoppingCartWebDescriptionShowCheckoutButtonInPopup")> _
<LocalizedCategoryAttribute("MiniShoppingCartCustomPropertiesCategoryName")> _
Public Property ShowCheckoutButtonInPopup As Boolean
    Get
    Set
'Usage
Dim instance As MiniShoppingCart
Dim value As Boolean

value = instance.ShowCheckoutButtonInPopup

instance.ShowCheckoutButtonInPopup = value
```

``` csharp
[PersonalizableAttribute(PersonalizationScope.Shared)]
[LocalizedWebDisplayNameAttribute("MiniShoppingCartWebDisplayNameShowCheckoutButtonInPopup")]
[WebBrowsableAttribute(true)]
[WebPartStorageAttribute(Storage.Shared)]
[LocalizedWebDescriptionAttribute("MiniShoppingCartWebDescriptionShowCheckoutButtonInPopup")]
[LocalizedCategoryAttribute("MiniShoppingCartCustomPropertiesCategoryName")]
public bool ShowCheckoutButtonInPopup { get; set; }
```

``` c++
[PersonalizableAttribute(PersonalizationScope::Shared)]
[LocalizedWebDisplayNameAttribute(L"MiniShoppingCartWebDisplayNameShowCheckoutButtonInPopup")]
[WebBrowsableAttribute(true)]
[WebPartStorageAttribute(Storage::Shared)]
[LocalizedWebDescriptionAttribute(L"MiniShoppingCartWebDescriptionShowCheckoutButtonInPopup")]
[LocalizedCategoryAttribute(L"MiniShoppingCartCustomPropertiesCategoryName")]
public:
property bool ShowCheckoutButtonInPopup {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[MiniShoppingCart Class](minishoppingcart-class-microsoft-dynamics-retail-sharepoint-web-webparts.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.WebParts Namespace](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)

