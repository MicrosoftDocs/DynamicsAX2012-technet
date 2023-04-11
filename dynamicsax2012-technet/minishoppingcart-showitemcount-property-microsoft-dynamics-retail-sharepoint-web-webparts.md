---
title: MiniShoppingCart.ShowItemCount Property  (Microsoft.Dynamics.Retail.SharePoint.Web.WebParts)
TOCTitle: ShowItemCount Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.MiniShoppingCart.ShowItemCount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.webparts.minishoppingcart.showitemcount(v=AX.60)
ms:contentKeyID: 62205068
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.MiniShoppingCart.ShowItemCount
dev_langs:
- CSharp
- C++
- VB
---

# ShowItemCount Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets whether to show or hide the shopping cart item count. This is true by default.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.WebParts](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.WebParts (in Microsoft.Dynamics.Retail.SP.Web.WebParts.dll)

## Syntax

``` vb
'Declaration
<WebBrowsableAttribute(True)> _
<WebPartStorageAttribute(Storage.Shared)> _
<LocalizedWebDisplayNameAttribute("MiniShoppingCartWebDisplayNameShowItemCount")> _
<LocalizedWebDescriptionAttribute("MiniShoppingCartWebDescriptionShowItemCount")> _
<LocalizedCategoryAttribute("MiniShoppingCartCustomPropertiesCategoryName")> _
<PersonalizableAttribute(PersonalizationScope.Shared)> _
Public Property ShowItemCount As Boolean
    Get
    Set
'Usage
Dim instance As MiniShoppingCart
Dim value As Boolean

value = instance.ShowItemCount

instance.ShowItemCount = value
```

``` csharp
[WebBrowsableAttribute(true)]
[WebPartStorageAttribute(Storage.Shared)]
[LocalizedWebDisplayNameAttribute("MiniShoppingCartWebDisplayNameShowItemCount")]
[LocalizedWebDescriptionAttribute("MiniShoppingCartWebDescriptionShowItemCount")]
[LocalizedCategoryAttribute("MiniShoppingCartCustomPropertiesCategoryName")]
[PersonalizableAttribute(PersonalizationScope.Shared)]
public bool ShowItemCount { get; set; }
```

``` c++
[WebBrowsableAttribute(true)]
[WebPartStorageAttribute(Storage::Shared)]
[LocalizedWebDisplayNameAttribute(L"MiniShoppingCartWebDisplayNameShowItemCount")]
[LocalizedWebDescriptionAttribute(L"MiniShoppingCartWebDescriptionShowItemCount")]
[LocalizedCategoryAttribute(L"MiniShoppingCartCustomPropertiesCategoryName")]
[PersonalizableAttribute(PersonalizationScope::Shared)]
public:
property bool ShowItemCount {
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

