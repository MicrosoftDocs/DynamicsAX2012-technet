---
title: ShoppingCart.ShowFooterSubtotals Property  (Microsoft.Dynamics.Retail.SharePoint.Web.WebParts)
TOCTitle: ShowFooterSubtotals Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.ShoppingCart.ShowFooterSubtotals
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.web.webparts.shoppingcart.showfootersubtotals(v=AX.60)
ms:contentKeyID: 62205490
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.ShoppingCart.ShowFooterSubtotals
dev_langs:
- CSharp
- C++
- VB
---

# ShowFooterSubtotals Property

Gets or sets whether to show subtotals in the footer.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.WebParts](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.WebParts (in Microsoft.Dynamics.Retail.SP.Web.WebParts.dll)

## Syntax

``` vb
'Declaration
<WebPartStorageAttribute(Storage.Shared)> _
<LocalizedWebDescriptionAttribute("ShoppingCartWebDescriptionShowFooterSubtotals")> _
<PersonalizableAttribute(PersonalizationScope.Shared)> _
<LocalizedWebDisplayNameAttribute("ShoppingCartWebDisplayNameShowFooterSubtotals")> _
<LocalizedCategoryAttribute("ShoppingCartCustomPropertiesCategoryName")> _
<WebBrowsableAttribute(True)> _
Public Property ShowFooterSubtotals As Boolean
    Get
    Set
'Usage
Dim instance As ShoppingCart
Dim value As Boolean

value = instance.ShowFooterSubtotals

instance.ShowFooterSubtotals = value
```

``` csharp
[WebPartStorageAttribute(Storage.Shared)]
[LocalizedWebDescriptionAttribute("ShoppingCartWebDescriptionShowFooterSubtotals")]
[PersonalizableAttribute(PersonalizationScope.Shared)]
[LocalizedWebDisplayNameAttribute("ShoppingCartWebDisplayNameShowFooterSubtotals")]
[LocalizedCategoryAttribute("ShoppingCartCustomPropertiesCategoryName")]
[WebBrowsableAttribute(true)]
public bool ShowFooterSubtotals { get; set; }
```

``` c++
[WebPartStorageAttribute(Storage::Shared)]
[LocalizedWebDescriptionAttribute(L"ShoppingCartWebDescriptionShowFooterSubtotals")]
[PersonalizableAttribute(PersonalizationScope::Shared)]
[LocalizedWebDisplayNameAttribute(L"ShoppingCartWebDisplayNameShowFooterSubtotals")]
[LocalizedCategoryAttribute(L"ShoppingCartCustomPropertiesCategoryName")]
[WebBrowsableAttribute(true)]
public:
property bool ShowFooterSubtotals {
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

