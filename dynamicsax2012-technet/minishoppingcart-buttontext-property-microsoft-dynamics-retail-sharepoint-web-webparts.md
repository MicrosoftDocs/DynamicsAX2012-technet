---
title: MiniShoppingCart.ButtonText Property  (Microsoft.Dynamics.Retail.SharePoint.Web.WebParts)
TOCTitle: ButtonText Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.MiniShoppingCart.ButtonText
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.webparts.minishoppingcart.buttontext(v=AX.60)
ms:contentKeyID: 62205607
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.MiniShoppingCart.ButtonText
dev_langs:
- CSharp
- C++
- VB
---

# ButtonText Property

Gets or sets the button text. Default is 'Cart'.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.WebParts](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.WebParts (in Microsoft.Dynamics.Retail.SP.Web.WebParts.dll)

## Syntax

``` vb
'Declaration
<LocalizedCategoryAttribute("MiniShoppingCartCustomPropertiesCategoryName")> _
<WebPartStorageAttribute(Storage.Shared)> _
<LocalizedWebDescriptionAttribute("MiniShoppingCartWebDescriptionButtonText")> _
<LocalizedWebDisplayNameAttribute("MiniShoppingCartWebDisplayNameButtonText")> _
<WebBrowsableAttribute(True)> _
<PersonalizableAttribute(PersonalizationScope.Shared)> _
Public Property ButtonText As String
    Get
    Set
'Usage
Dim instance As MiniShoppingCart
Dim value As String

value = instance.ButtonText

instance.ButtonText = value
```

``` csharp
[LocalizedCategoryAttribute("MiniShoppingCartCustomPropertiesCategoryName")]
[WebPartStorageAttribute(Storage.Shared)]
[LocalizedWebDescriptionAttribute("MiniShoppingCartWebDescriptionButtonText")]
[LocalizedWebDisplayNameAttribute("MiniShoppingCartWebDisplayNameButtonText")]
[WebBrowsableAttribute(true)]
[PersonalizableAttribute(PersonalizationScope.Shared)]
public string ButtonText { get; set; }
```

``` c++
[LocalizedCategoryAttribute(L"MiniShoppingCartCustomPropertiesCategoryName")]
[WebPartStorageAttribute(Storage::Shared)]
[LocalizedWebDescriptionAttribute(L"MiniShoppingCartWebDescriptionButtonText")]
[LocalizedWebDisplayNameAttribute(L"MiniShoppingCartWebDisplayNameButtonText")]
[WebBrowsableAttribute(true)]
[PersonalizableAttribute(PersonalizationScope::Shared)]
public:
property String^ ButtonText {
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

