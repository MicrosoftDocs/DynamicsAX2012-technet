---
title: ShoppingCart.ShowFooterDiscounts Property  (Microsoft.Dynamics.Retail.SharePoint.Web.WebParts)
TOCTitle: ShowFooterDiscounts Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.ShoppingCart.ShowFooterDiscounts
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.webparts.shoppingcart.showfooterdiscounts(v=AX.60)
ms:contentKeyID: 62204281
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.ShoppingCart.ShowFooterDiscounts
dev_langs:
- CSharp
- C++
- VB
---

# ShowFooterDiscounts Property

Gets or sets whether to show discounts in the footer.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.WebParts](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.WebParts (in Microsoft.Dynamics.Retail.SP.Web.WebParts.dll)

## Syntax

``` vb
'Declaration
<PersonalizableAttribute(PersonalizationScope.Shared)> _
<WebPartStorageAttribute(Storage.Shared)> _
<LocalizedWebDisplayNameAttribute("ShoppingCartWebDisplayNameShowFooterDiscounts")> _
<LocalizedWebDescriptionAttribute("ShoppingCartWebDescriptionShowFooterDiscounts")> _
<LocalizedCategoryAttribute("ShoppingCartCustomPropertiesCategoryName")> _
<WebBrowsableAttribute(True)> _
Public Property ShowFooterDiscounts As Boolean
    Get
    Set
'Usage
Dim instance As ShoppingCart
Dim value As Boolean

value = instance.ShowFooterDiscounts

instance.ShowFooterDiscounts = value
```

``` csharp
[PersonalizableAttribute(PersonalizationScope.Shared)]
[WebPartStorageAttribute(Storage.Shared)]
[LocalizedWebDisplayNameAttribute("ShoppingCartWebDisplayNameShowFooterDiscounts")]
[LocalizedWebDescriptionAttribute("ShoppingCartWebDescriptionShowFooterDiscounts")]
[LocalizedCategoryAttribute("ShoppingCartCustomPropertiesCategoryName")]
[WebBrowsableAttribute(true)]
public bool ShowFooterDiscounts { get; set; }
```

``` c++
[PersonalizableAttribute(PersonalizationScope::Shared)]
[WebPartStorageAttribute(Storage::Shared)]
[LocalizedWebDisplayNameAttribute(L"ShoppingCartWebDisplayNameShowFooterDiscounts")]
[LocalizedWebDescriptionAttribute(L"ShoppingCartWebDescriptionShowFooterDiscounts")]
[LocalizedCategoryAttribute(L"ShoppingCartCustomPropertiesCategoryName")]
[WebBrowsableAttribute(true)]
public:
property bool ShowFooterDiscounts {
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

