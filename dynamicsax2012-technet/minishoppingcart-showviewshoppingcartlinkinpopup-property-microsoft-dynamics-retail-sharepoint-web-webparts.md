---
title: MiniShoppingCart.ShowViewShoppingCartLinkInPopup Property  (Microsoft.Dynamics.Retail.SharePoint.Web.WebParts)
TOCTitle: ShowViewShoppingCartLinkInPopup Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.MiniShoppingCart.ShowViewShoppingCartLinkInPopup
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.webparts.minishoppingcart.showviewshoppingcartlinkinpopup(v=AX.60)
ms:contentKeyID: 62205069
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.MiniShoppingCart.ShowViewShoppingCartLinkInPopup
dev_langs:
- CSharp
- C++
- VB
---

# ShowViewShoppingCartLinkInPopup Property

Gets or sets whether to show the Shopping Cart Link in the popup.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.WebParts](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.WebParts (in Microsoft.Dynamics.Retail.SP.Web.WebParts.dll)

## Syntax

``` vb
'Declaration
<LocalizedWebDisplayNameAttribute("MiniShoppingCartWebDisplayNameShowViewShoppingCartLinkInPopup")> _
<LocalizedCategoryAttribute("MiniShoppingCartCustomPropertiesCategoryName")> _
<WebPartStorageAttribute(Storage.Shared)> _
<WebBrowsableAttribute(True)> _
<PersonalizableAttribute(PersonalizationScope.Shared)> _
<LocalizedWebDescriptionAttribute("MiniShoppingCartWebDescriptionShowViewShoppingCartLinkInPopup")> _
Public Property ShowViewShoppingCartLinkInPopup As Boolean
    Get
    Set
'Usage
Dim instance As MiniShoppingCart
Dim value As Boolean

value = instance.ShowViewShoppingCartLinkInPopup

instance.ShowViewShoppingCartLinkInPopup = value
```

``` csharp
[LocalizedWebDisplayNameAttribute("MiniShoppingCartWebDisplayNameShowViewShoppingCartLinkInPopup")]
[LocalizedCategoryAttribute("MiniShoppingCartCustomPropertiesCategoryName")]
[WebPartStorageAttribute(Storage.Shared)]
[WebBrowsableAttribute(true)]
[PersonalizableAttribute(PersonalizationScope.Shared)]
[LocalizedWebDescriptionAttribute("MiniShoppingCartWebDescriptionShowViewShoppingCartLinkInPopup")]
public bool ShowViewShoppingCartLinkInPopup { get; set; }
```

``` c++
[LocalizedWebDisplayNameAttribute(L"MiniShoppingCartWebDisplayNameShowViewShoppingCartLinkInPopup")]
[LocalizedCategoryAttribute(L"MiniShoppingCartCustomPropertiesCategoryName")]
[WebPartStorageAttribute(Storage::Shared)]
[WebBrowsableAttribute(true)]
[PersonalizableAttribute(PersonalizationScope::Shared)]
[LocalizedWebDescriptionAttribute(L"MiniShoppingCartWebDescriptionShowViewShoppingCartLinkInPopup")]
public:
property bool ShowViewShoppingCartLinkInPopup {
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

