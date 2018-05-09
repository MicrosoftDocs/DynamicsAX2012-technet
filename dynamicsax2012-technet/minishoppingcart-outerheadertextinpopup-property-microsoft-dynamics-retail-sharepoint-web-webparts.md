---
title: MiniShoppingCart.OuterHeaderTextInPopup Property  (Microsoft.Dynamics.Retail.SharePoint.Web.WebParts)
TOCTitle: OuterHeaderTextInPopup Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.MiniShoppingCart.OuterHeaderTextInPopup
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.web.webparts.minishoppingcart.outerheadertextinpopup(v=AX.60)
ms:contentKeyID: 62206139
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.MiniShoppingCart.OuterHeaderTextInPopup
dev_langs:
- CSharp
- C++
- VB
---

# OuterHeaderTextInPopup Property

Gets or sets the mini-shopping cart header text. (outside container)

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.WebParts](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.WebParts (in Microsoft.Dynamics.Retail.SP.Web.WebParts.dll)

## Syntax

``` vb
'Declaration
<WebBrowsableAttribute(True)> _
<LocalizedWebDisplayNameAttribute("MiniShoppingCartWebDisplayNameOuterHeaderTextInPopup")> _
<PersonalizableAttribute(PersonalizationScope.Shared)> _
<LocalizedCategoryAttribute("MiniShoppingCartCustomPropertiesCategoryName")> _
<WebPartStorageAttribute(Storage.Shared)> _
<LocalizedWebDescriptionAttribute("MiniShoppingCartWebDescriptionOuterHeaderTextInPopup")> _
Public Property OuterHeaderTextInPopup As String
    Get
    Set
'Usage
Dim instance As MiniShoppingCart
Dim value As String

value = instance.OuterHeaderTextInPopup

instance.OuterHeaderTextInPopup = value
```

``` csharp
[WebBrowsableAttribute(true)]
[LocalizedWebDisplayNameAttribute("MiniShoppingCartWebDisplayNameOuterHeaderTextInPopup")]
[PersonalizableAttribute(PersonalizationScope.Shared)]
[LocalizedCategoryAttribute("MiniShoppingCartCustomPropertiesCategoryName")]
[WebPartStorageAttribute(Storage.Shared)]
[LocalizedWebDescriptionAttribute("MiniShoppingCartWebDescriptionOuterHeaderTextInPopup")]
public string OuterHeaderTextInPopup { get; set; }
```

``` c++
[WebBrowsableAttribute(true)]
[LocalizedWebDisplayNameAttribute(L"MiniShoppingCartWebDisplayNameOuterHeaderTextInPopup")]
[PersonalizableAttribute(PersonalizationScope::Shared)]
[LocalizedCategoryAttribute(L"MiniShoppingCartCustomPropertiesCategoryName")]
[WebPartStorageAttribute(Storage::Shared)]
[LocalizedWebDescriptionAttribute(L"MiniShoppingCartWebDescriptionOuterHeaderTextInPopup")]
public:
property String^ OuterHeaderTextInPopup {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[MiniShoppingCart Class](minishoppingcart-class-microsoft-dynamics-retail-sharepoint-web-webparts.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.WebParts Namespace](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)

