---
title: ShoppingCart.ShowFooterHeader Property  (Microsoft.Dynamics.Retail.SharePoint.Web.WebParts)
TOCTitle: ShowFooterHeader Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.ShoppingCart.ShowFooterHeader
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.web.webparts.shoppingcart.showfooterheader(v=AX.60)
ms:contentKeyID: 62206053
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.ShoppingCart.ShowFooterHeader
dev_langs:
- CSharp
- C++
- VB
---

# ShowFooterHeader Property

Gets or sets whether to show the footer summary rows. Default is true.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.WebParts](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.WebParts (in Microsoft.Dynamics.Retail.SP.Web.WebParts.dll)

## Syntax

``` vb
'Declaration
<WebBrowsableAttribute(True)> _
<LocalizedWebDisplayNameAttribute("ShoppingCartWebDisplayNameShowFooterHeader")> _
<WebPartStorageAttribute(Storage.Shared)> _
<LocalizedWebDescriptionAttribute("ShoppingCartWebDescriptionShowFooterHeader")> _
<LocalizedCategoryAttribute("ShoppingCartCustomPropertiesCategoryName")> _
<PersonalizableAttribute(PersonalizationScope.Shared)> _
Public Property ShowFooterHeader As Boolean
    Get
    Set
'Usage
Dim instance As ShoppingCart
Dim value As Boolean

value = instance.ShowFooterHeader

instance.ShowFooterHeader = value
```

``` csharp
[WebBrowsableAttribute(true)]
[LocalizedWebDisplayNameAttribute("ShoppingCartWebDisplayNameShowFooterHeader")]
[WebPartStorageAttribute(Storage.Shared)]
[LocalizedWebDescriptionAttribute("ShoppingCartWebDescriptionShowFooterHeader")]
[LocalizedCategoryAttribute("ShoppingCartCustomPropertiesCategoryName")]
[PersonalizableAttribute(PersonalizationScope.Shared)]
public bool ShowFooterHeader { get; set; }
```

``` c++
[WebBrowsableAttribute(true)]
[LocalizedWebDisplayNameAttribute(L"ShoppingCartWebDisplayNameShowFooterHeader")]
[WebPartStorageAttribute(Storage::Shared)]
[LocalizedWebDescriptionAttribute(L"ShoppingCartWebDescriptionShowFooterHeader")]
[LocalizedCategoryAttribute(L"ShoppingCartCustomPropertiesCategoryName")]
[PersonalizableAttribute(PersonalizationScope::Shared)]
public:
property bool ShowFooterHeader {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[ShoppingCart Class](shoppingcart-class-microsoft-dynamics-retail-sharepoint-web-webparts.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.WebParts Namespace](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)

