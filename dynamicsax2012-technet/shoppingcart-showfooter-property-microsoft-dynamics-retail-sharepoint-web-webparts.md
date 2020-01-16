---
title: ShoppingCart.ShowFooter Property  (Microsoft.Dynamics.Retail.SharePoint.Web.WebParts)
TOCTitle: ShowFooter Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.ShoppingCart.ShowFooter
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.webparts.shoppingcart.showfooter(v=AX.60)
ms:contentKeyID: 62206637
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.ShoppingCart.ShowFooter
dev_langs:
- CSharp
- C++
- VB
---

# ShowFooter Property

Gets or sets whether to show the footer.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.WebParts](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.WebParts (in Microsoft.Dynamics.Retail.SP.Web.WebParts.dll)

## Syntax

``` vb
'Declaration
<WebBrowsableAttribute(True)> _
<PersonalizableAttribute(PersonalizationScope.Shared)> _
<WebPartStorageAttribute(Storage.Shared)> _
<LocalizedWebDescriptionAttribute("ShoppingCartWebDescriptionShowFooter")> _
<LocalizedCategoryAttribute("ShoppingCartCustomPropertiesCategoryName")> _
<LocalizedWebDisplayNameAttribute("ShoppingCartWebDisplayNameShowFooter")> _
Public Property ShowFooter As Boolean
    Get
    Set
'Usage
Dim instance As ShoppingCart
Dim value As Boolean

value = instance.ShowFooter

instance.ShowFooter = value
```

``` csharp
[WebBrowsableAttribute(true)]
[PersonalizableAttribute(PersonalizationScope.Shared)]
[WebPartStorageAttribute(Storage.Shared)]
[LocalizedWebDescriptionAttribute("ShoppingCartWebDescriptionShowFooter")]
[LocalizedCategoryAttribute("ShoppingCartCustomPropertiesCategoryName")]
[LocalizedWebDisplayNameAttribute("ShoppingCartWebDisplayNameShowFooter")]
public bool ShowFooter { get; set; }
```

``` c++
[WebBrowsableAttribute(true)]
[PersonalizableAttribute(PersonalizationScope::Shared)]
[WebPartStorageAttribute(Storage::Shared)]
[LocalizedWebDescriptionAttribute(L"ShoppingCartWebDescriptionShowFooter")]
[LocalizedCategoryAttribute(L"ShoppingCartCustomPropertiesCategoryName")]
[LocalizedWebDisplayNameAttribute(L"ShoppingCartWebDisplayNameShowFooter")]
public:
property bool ShowFooter {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[ShoppingCart Class](shoppingcart-class-microsoft-dynamics-retail-sharepoint-web-webparts.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.WebParts Namespace](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)

