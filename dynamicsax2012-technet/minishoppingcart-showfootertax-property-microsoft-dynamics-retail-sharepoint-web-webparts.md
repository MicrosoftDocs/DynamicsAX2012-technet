---
title: MiniShoppingCart.ShowFooterTax Property  (Microsoft.Dynamics.Retail.SharePoint.Web.WebParts)
TOCTitle: ShowFooterTax Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.MiniShoppingCart.ShowFooterTax
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.webparts.minishoppingcart.showfootertax(v=AX.60)
ms:contentKeyID: 62206605
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.MiniShoppingCart.ShowFooterTax
dev_langs:
- CSharp
- C++
- VB
---

# ShowFooterTax Property

Gets or sets whether to show the footer summary sales tax row. Default is false.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.WebParts](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.WebParts (in Microsoft.Dynamics.Retail.SP.Web.WebParts.dll)

## Syntax

``` vb
'Declaration
<LocalizedWebDisplayNameAttribute("MiniShoppingCartWebDisplayNameShowFooterTax")> _
<PersonalizableAttribute(PersonalizationScope.Shared)> _
<LocalizedCategoryAttribute("MiniShoppingCartCustomPropertiesCategoryName")> _
<WebPartStorageAttribute(Storage.Shared)> _
<LocalizedWebDescriptionAttribute("MiniShoppingCartWebDescriptionShowFooterTax")> _
<WebBrowsableAttribute(True)> _
Public Property ShowFooterTax As Boolean
    Get
    Set
'Usage
Dim instance As MiniShoppingCart
Dim value As Boolean

value = instance.ShowFooterTax

instance.ShowFooterTax = value
```

``` csharp
[LocalizedWebDisplayNameAttribute("MiniShoppingCartWebDisplayNameShowFooterTax")]
[PersonalizableAttribute(PersonalizationScope.Shared)]
[LocalizedCategoryAttribute("MiniShoppingCartCustomPropertiesCategoryName")]
[WebPartStorageAttribute(Storage.Shared)]
[LocalizedWebDescriptionAttribute("MiniShoppingCartWebDescriptionShowFooterTax")]
[WebBrowsableAttribute(true)]
public bool ShowFooterTax { get; set; }
```

``` c++
[LocalizedWebDisplayNameAttribute(L"MiniShoppingCartWebDisplayNameShowFooterTax")]
[PersonalizableAttribute(PersonalizationScope::Shared)]
[LocalizedCategoryAttribute(L"MiniShoppingCartCustomPropertiesCategoryName")]
[WebPartStorageAttribute(Storage::Shared)]
[LocalizedWebDescriptionAttribute(L"MiniShoppingCartWebDescriptionShowFooterTax")]
[WebBrowsableAttribute(true)]
public:
property bool ShowFooterTax {
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

