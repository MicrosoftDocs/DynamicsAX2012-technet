---
title: MiniShoppingCart.ShowFooter Property  (Microsoft.Dynamics.Retail.SharePoint.Web.WebParts)
TOCTitle: ShowFooter Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.MiniShoppingCart.ShowFooter
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.webparts.minishoppingcart.showfooter(v=AX.60)
ms:contentKeyID: 62205478
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.MiniShoppingCart.ShowFooter
dev_langs:
- CSharp
- C++
- VB
---

# ShowFooter Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets whether to show the footer.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.WebParts](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.WebParts (in Microsoft.Dynamics.Retail.SP.Web.WebParts.dll)

## Syntax

``` vb
'Declaration
<WebPartStorageAttribute(Storage.Shared)> _
<PersonalizableAttribute(PersonalizationScope.Shared)> _
<LocalizedCategoryAttribute("MiniShoppingCartCustomPropertiesCategoryName")> _
<LocalizedWebDescriptionAttribute("MiniShoppingCartWebDescriptionShowFooter")> _
<WebBrowsableAttribute(True)> _
<LocalizedWebDisplayNameAttribute("MiniShoppingCartWebDisplayNameShowFooter")> _
Public Property ShowFooter As Boolean
    Get
    Set
'Usage
Dim instance As MiniShoppingCart
Dim value As Boolean

value = instance.ShowFooter

instance.ShowFooter = value
```

``` csharp
[WebPartStorageAttribute(Storage.Shared)]
[PersonalizableAttribute(PersonalizationScope.Shared)]
[LocalizedCategoryAttribute("MiniShoppingCartCustomPropertiesCategoryName")]
[LocalizedWebDescriptionAttribute("MiniShoppingCartWebDescriptionShowFooter")]
[WebBrowsableAttribute(true)]
[LocalizedWebDisplayNameAttribute("MiniShoppingCartWebDisplayNameShowFooter")]
public bool ShowFooter { get; set; }
```

``` c++
[WebPartStorageAttribute(Storage::Shared)]
[PersonalizableAttribute(PersonalizationScope::Shared)]
[LocalizedCategoryAttribute(L"MiniShoppingCartCustomPropertiesCategoryName")]
[LocalizedWebDescriptionAttribute(L"MiniShoppingCartWebDescriptionShowFooter")]
[WebBrowsableAttribute(true)]
[LocalizedWebDisplayNameAttribute(L"MiniShoppingCartWebDisplayNameShowFooter")]
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

[MiniShoppingCart Class](minishoppingcart-class-microsoft-dynamics-retail-sharepoint-web-webparts.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.WebParts Namespace](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)

