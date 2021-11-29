---
title: MiniShoppingCart.InnerHeaderTextInPopup Property  (Microsoft.Dynamics.Retail.SharePoint.Web.WebParts)
TOCTitle: InnerHeaderTextInPopup Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.MiniShoppingCart.InnerHeaderTextInPopup
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.webparts.minishoppingcart.innerheadertextinpopup(v=AX.60)
ms:contentKeyID: 62206373
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.MiniShoppingCart.InnerHeaderTextInPopup
dev_langs:
- CSharp
- C++
- VB
---

# InnerHeaderTextInPopup Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the mini-shopping cart header text. (within container)

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.WebParts](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.WebParts (in Microsoft.Dynamics.Retail.SP.Web.WebParts.dll)

## Syntax

``` vb
'Declaration
<LocalizedWebDisplayNameAttribute("MiniShoppingCartWebDisplayNameInnerHeaderTextInPopup")> _
<WebPartStorageAttribute(Storage.Shared)> _
<LocalizedWebDescriptionAttribute("MiniShoppingCartWebDescriptionInnerHeaderTextInPopup")> _
<LocalizedCategoryAttribute("MiniShoppingCartCustomPropertiesCategoryName")> _
<WebBrowsableAttribute(True)> _
<PersonalizableAttribute(PersonalizationScope.Shared)> _
Public Property InnerHeaderTextInPopup As String
    Get
    Set
'Usage
Dim instance As MiniShoppingCart
Dim value As String

value = instance.InnerHeaderTextInPopup

instance.InnerHeaderTextInPopup = value
```

``` csharp
[LocalizedWebDisplayNameAttribute("MiniShoppingCartWebDisplayNameInnerHeaderTextInPopup")]
[WebPartStorageAttribute(Storage.Shared)]
[LocalizedWebDescriptionAttribute("MiniShoppingCartWebDescriptionInnerHeaderTextInPopup")]
[LocalizedCategoryAttribute("MiniShoppingCartCustomPropertiesCategoryName")]
[WebBrowsableAttribute(true)]
[PersonalizableAttribute(PersonalizationScope.Shared)]
public string InnerHeaderTextInPopup { get; set; }
```

``` c++
[LocalizedWebDisplayNameAttribute(L"MiniShoppingCartWebDisplayNameInnerHeaderTextInPopup")]
[WebPartStorageAttribute(Storage::Shared)]
[LocalizedWebDescriptionAttribute(L"MiniShoppingCartWebDescriptionInnerHeaderTextInPopup")]
[LocalizedCategoryAttribute(L"MiniShoppingCartCustomPropertiesCategoryName")]
[WebBrowsableAttribute(true)]
[PersonalizableAttribute(PersonalizationScope::Shared)]
public:
property String^ InnerHeaderTextInPopup {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[MiniShoppingCart Class](minishoppingcart-class-microsoft-dynamics-retail-sharepoint-web-webparts.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.WebParts Namespace](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)

