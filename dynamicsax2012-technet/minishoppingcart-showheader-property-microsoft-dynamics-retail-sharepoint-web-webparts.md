---
title: MiniShoppingCart.ShowHeader Property  (Microsoft.Dynamics.Retail.SharePoint.Web.WebParts)
TOCTitle: ShowHeader Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.MiniShoppingCart.ShowHeader
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.web.webparts.minishoppingcart.showheader(v=AX.60)
ms:contentKeyID: 62207020
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.MiniShoppingCart.ShowHeader
dev_langs:
- CSharp
- C++
- VB
---

# ShowHeader Property

Gets or sets whether to show the column headers.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.WebParts](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.WebParts (in Microsoft.Dynamics.Retail.SP.Web.WebParts.dll)

## Syntax

``` vb
'Declaration
<LocalizedCategoryAttribute("MiniShoppingCartCustomPropertiesCategoryName")> _
<PersonalizableAttribute(PersonalizationScope.Shared)> _
<WebPartStorageAttribute(Storage.Shared)> _
<LocalizedWebDescriptionAttribute("MiniShoppingCartWebDescriptionShowHeader")> _
<WebBrowsableAttribute(True)> _
<LocalizedWebDisplayNameAttribute("MiniShoppingCartWebDisplayNameShowHeader")> _
Public Property ShowHeader As Boolean
    Get
    Set
'Usage
Dim instance As MiniShoppingCart
Dim value As Boolean

value = instance.ShowHeader

instance.ShowHeader = value
```

``` csharp
[LocalizedCategoryAttribute("MiniShoppingCartCustomPropertiesCategoryName")]
[PersonalizableAttribute(PersonalizationScope.Shared)]
[WebPartStorageAttribute(Storage.Shared)]
[LocalizedWebDescriptionAttribute("MiniShoppingCartWebDescriptionShowHeader")]
[WebBrowsableAttribute(true)]
[LocalizedWebDisplayNameAttribute("MiniShoppingCartWebDisplayNameShowHeader")]
public bool ShowHeader { get; set; }
```

``` c++
[LocalizedCategoryAttribute(L"MiniShoppingCartCustomPropertiesCategoryName")]
[PersonalizableAttribute(PersonalizationScope::Shared)]
[WebPartStorageAttribute(Storage::Shared)]
[LocalizedWebDescriptionAttribute(L"MiniShoppingCartWebDescriptionShowHeader")]
[WebBrowsableAttribute(true)]
[LocalizedWebDisplayNameAttribute(L"MiniShoppingCartWebDisplayNameShowHeader")]
public:
property bool ShowHeader {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[MiniShoppingCart Class](minishoppingcart-class-microsoft-dynamics-retail-sharepoint-web-webparts.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.WebParts Namespace](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)

