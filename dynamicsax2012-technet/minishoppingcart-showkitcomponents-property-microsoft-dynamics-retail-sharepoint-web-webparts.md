---
title: MiniShoppingCart.ShowKitComponents Property  (Microsoft.Dynamics.Retail.SharePoint.Web.WebParts)
TOCTitle: ShowKitComponents Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.MiniShoppingCart.ShowKitComponents
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.web.webparts.minishoppingcart.showkitcomponents(v=AX.60)
ms:contentKeyID: 62205393
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.MiniShoppingCart.ShowKitComponents
dev_langs:
- CSharp
- C++
- VB
---

# ShowKitComponents Property

Gets or sets whether to show the kit components when the shopping cart has kit items.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.WebParts](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.WebParts (in Microsoft.Dynamics.Retail.SP.Web.WebParts.dll)

## Syntax

``` vb
'Declaration
<LocalizedCategoryAttribute("MiniShoppingCartCustomPropertiesCategoryName")> _
<PersonalizableAttribute(PersonalizationScope.Shared)> _
<WebPartStorageAttribute(Storage.Shared)> _
<LocalizedWebDisplayNameAttribute("MiniShoppingCartWebDisplayNameShowKitComponents")> _
<LocalizedWebDescriptionAttribute("MiniShoppingCartWebDescriptionShowKitComponents")> _
<WebBrowsableAttribute(True)> _
Public Property ShowKitComponents As Boolean
    Get
    Set
'Usage
Dim instance As MiniShoppingCart
Dim value As Boolean

value = instance.ShowKitComponents

instance.ShowKitComponents = value
```

``` csharp
[LocalizedCategoryAttribute("MiniShoppingCartCustomPropertiesCategoryName")]
[PersonalizableAttribute(PersonalizationScope.Shared)]
[WebPartStorageAttribute(Storage.Shared)]
[LocalizedWebDisplayNameAttribute("MiniShoppingCartWebDisplayNameShowKitComponents")]
[LocalizedWebDescriptionAttribute("MiniShoppingCartWebDescriptionShowKitComponents")]
[WebBrowsableAttribute(true)]
public bool ShowKitComponents { get; set; }
```

``` c++
[LocalizedCategoryAttribute(L"MiniShoppingCartCustomPropertiesCategoryName")]
[PersonalizableAttribute(PersonalizationScope::Shared)]
[WebPartStorageAttribute(Storage::Shared)]
[LocalizedWebDisplayNameAttribute(L"MiniShoppingCartWebDisplayNameShowKitComponents")]
[LocalizedWebDescriptionAttribute(L"MiniShoppingCartWebDescriptionShowKitComponents")]
[WebBrowsableAttribute(true)]
public:
property bool ShowKitComponents {
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

