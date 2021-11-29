---
title: ShoppingCart.ShowFooterTax Property  (Microsoft.Dynamics.Retail.SharePoint.Web.WebParts)
TOCTitle: ShowFooterTax Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.ShoppingCart.ShowFooterTax
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.webparts.shoppingcart.showfootertax(v=AX.60)
ms:contentKeyID: 62202951
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.ShoppingCart.ShowFooterTax
dev_langs:
- CSharp
- C++
- VB
---

# ShowFooterTax Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets whether to show tax in the footer.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.WebParts](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.WebParts (in Microsoft.Dynamics.Retail.SP.Web.WebParts.dll)

## Syntax

``` vb
'Declaration
<WebBrowsableAttribute(True)> _
<LocalizedWebDisplayNameAttribute("ShoppingCartWebDisplayNameShowFooterTax")> _
<PersonalizableAttribute(PersonalizationScope.Shared)> _
<LocalizedWebDescriptionAttribute("ShoppingCartWebDescriptionShowFooterTax")> _
<LocalizedCategoryAttribute("ShoppingCartCustomPropertiesCategoryName")> _
<WebPartStorageAttribute(Storage.Shared)> _
Public Property ShowFooterTax As Boolean
    Get
    Set
'Usage
Dim instance As ShoppingCart
Dim value As Boolean

value = instance.ShowFooterTax

instance.ShowFooterTax = value
```

``` csharp
[WebBrowsableAttribute(true)]
[LocalizedWebDisplayNameAttribute("ShoppingCartWebDisplayNameShowFooterTax")]
[PersonalizableAttribute(PersonalizationScope.Shared)]
[LocalizedWebDescriptionAttribute("ShoppingCartWebDescriptionShowFooterTax")]
[LocalizedCategoryAttribute("ShoppingCartCustomPropertiesCategoryName")]
[WebPartStorageAttribute(Storage.Shared)]
public bool ShowFooterTax { get; set; }
```

``` c++
[WebBrowsableAttribute(true)]
[LocalizedWebDisplayNameAttribute(L"ShoppingCartWebDisplayNameShowFooterTax")]
[PersonalizableAttribute(PersonalizationScope::Shared)]
[LocalizedWebDescriptionAttribute(L"ShoppingCartWebDescriptionShowFooterTax")]
[LocalizedCategoryAttribute(L"ShoppingCartCustomPropertiesCategoryName")]
[WebPartStorageAttribute(Storage::Shared)]
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

[ShoppingCart Class](shoppingcart-class-microsoft-dynamics-retail-sharepoint-web-webparts.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.WebParts Namespace](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)

