---
title: MiniShoppingCart.ShowFooterGrandTotal Property  (Microsoft.Dynamics.Retail.SharePoint.Web.WebParts)
TOCTitle: ShowFooterGrandTotal Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.MiniShoppingCart.ShowFooterGrandTotal
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.webparts.minishoppingcart.showfootergrandtotal(v=AX.60)
ms:contentKeyID: 62204210
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.MiniShoppingCart.ShowFooterGrandTotal
dev_langs:
- CSharp
- C++
- VB
---

# ShowFooterGrandTotal Property

Gets or sets whether to show the footer summary grand total row. Default is false.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.WebParts](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.WebParts (in Microsoft.Dynamics.Retail.SP.Web.WebParts.dll)

## Syntax

``` vb
'Declaration
<LocalizedWebDisplayNameAttribute("MiniShoppingCartWebDisplayNameShowFooterGrandTotal")> _
<PersonalizableAttribute(PersonalizationScope.Shared)> _
<LocalizedCategoryAttribute("MiniShoppingCartCustomPropertiesCategoryName")> _
<WebPartStorageAttribute(Storage.Shared)> _
<LocalizedWebDescriptionAttribute("MiniShoppingCartWebDescriptionShowFooterGrandTotal")> _
<WebBrowsableAttribute(True)> _
Public Property ShowFooterGrandTotal As Boolean
    Get
    Set
'Usage
Dim instance As MiniShoppingCart
Dim value As Boolean

value = instance.ShowFooterGrandTotal

instance.ShowFooterGrandTotal = value
```

``` csharp
[LocalizedWebDisplayNameAttribute("MiniShoppingCartWebDisplayNameShowFooterGrandTotal")]
[PersonalizableAttribute(PersonalizationScope.Shared)]
[LocalizedCategoryAttribute("MiniShoppingCartCustomPropertiesCategoryName")]
[WebPartStorageAttribute(Storage.Shared)]
[LocalizedWebDescriptionAttribute("MiniShoppingCartWebDescriptionShowFooterGrandTotal")]
[WebBrowsableAttribute(true)]
public bool ShowFooterGrandTotal { get; set; }
```

``` c++
[LocalizedWebDisplayNameAttribute(L"MiniShoppingCartWebDisplayNameShowFooterGrandTotal")]
[PersonalizableAttribute(PersonalizationScope::Shared)]
[LocalizedCategoryAttribute(L"MiniShoppingCartCustomPropertiesCategoryName")]
[WebPartStorageAttribute(Storage::Shared)]
[LocalizedWebDescriptionAttribute(L"MiniShoppingCartWebDescriptionShowFooterGrandTotal")]
[WebBrowsableAttribute(true)]
public:
property bool ShowFooterGrandTotal {
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

