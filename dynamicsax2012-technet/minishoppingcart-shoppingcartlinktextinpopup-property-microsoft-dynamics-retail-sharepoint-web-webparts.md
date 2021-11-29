---
title: MiniShoppingCart.ShoppingCartLinkTextInPopup Property  (Microsoft.Dynamics.Retail.SharePoint.Web.WebParts)
TOCTitle: ShoppingCartLinkTextInPopup Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.MiniShoppingCart.ShoppingCartLinkTextInPopup
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.webparts.minishoppingcart.shoppingcartlinktextinpopup(v=AX.60)
ms:contentKeyID: 62207370
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.MiniShoppingCart.ShoppingCartLinkTextInPopup
dev_langs:
- CSharp
- C++
- VB
---

# ShoppingCartLinkTextInPopup Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the text to display in for the Shopping Cart Link in the Popup.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.WebParts](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.WebParts (in Microsoft.Dynamics.Retail.SP.Web.WebParts.dll)

## Syntax

``` vb
'Declaration
<LocalizedWebDisplayNameAttribute("MiniShoppingCartWebDisplayNameShoppingCartLinkTextInPopup")> _
<PersonalizableAttribute(PersonalizationScope.Shared)> _
<WebPartStorageAttribute(Storage.Shared)> _
<WebBrowsableAttribute(True)> _
<LocalizedCategoryAttribute("MiniShoppingCartCustomPropertiesCategoryName")> _
<LocalizedWebDescriptionAttribute("MiniShoppingCartWebDescriptionShoppingCartLinkTextInPopup")> _
Public Property ShoppingCartLinkTextInPopup As String
    Get
    Set
'Usage
Dim instance As MiniShoppingCart
Dim value As String

value = instance.ShoppingCartLinkTextInPopup

instance.ShoppingCartLinkTextInPopup = value
```

``` csharp
[LocalizedWebDisplayNameAttribute("MiniShoppingCartWebDisplayNameShoppingCartLinkTextInPopup")]
[PersonalizableAttribute(PersonalizationScope.Shared)]
[WebPartStorageAttribute(Storage.Shared)]
[WebBrowsableAttribute(true)]
[LocalizedCategoryAttribute("MiniShoppingCartCustomPropertiesCategoryName")]
[LocalizedWebDescriptionAttribute("MiniShoppingCartWebDescriptionShoppingCartLinkTextInPopup")]
public string ShoppingCartLinkTextInPopup { get; set; }
```

``` c++
[LocalizedWebDisplayNameAttribute(L"MiniShoppingCartWebDisplayNameShoppingCartLinkTextInPopup")]
[PersonalizableAttribute(PersonalizationScope::Shared)]
[WebPartStorageAttribute(Storage::Shared)]
[WebBrowsableAttribute(true)]
[LocalizedCategoryAttribute(L"MiniShoppingCartCustomPropertiesCategoryName")]
[LocalizedWebDescriptionAttribute(L"MiniShoppingCartWebDescriptionShoppingCartLinkTextInPopup")]
public:
property String^ ShoppingCartLinkTextInPopup {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[MiniShoppingCart Class](minishoppingcart-class-microsoft-dynamics-retail-sharepoint-web-webparts.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.WebParts Namespace](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)

