---
title: AddToCart.RedirectUrl Property  (Microsoft.Dynamics.Retail.SharePoint.Web.WebParts)
TOCTitle: RedirectUrl Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.AddToCart.RedirectUrl
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.webparts.addtocart.redirecturl(v=AX.60)
ms:contentKeyID: 62204061
author: tonyafehr
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.AddToCart.RedirectUrl
dev_langs:
- CSharp
- C++
- VB
---

# RedirectUrl Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the shopping cart page to redirect to after adding an item to the cart. Empty Url means no redirect.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.WebParts](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.WebParts (in Microsoft.Dynamics.Retail.SP.Web.WebParts.dll)

## Syntax

``` vb
'Declaration
<LocalizedCategoryAttribute("AddToCartCustomPropertiesSettings")> _
<PersonalizableAttribute(PersonalizationScope.Shared)> _
<LocalizedWebDisplayNameAttribute("AddToCartWebDisplayNameShoppingCartPageUrl")> _
<WebPartStorageAttribute(Storage.Shared)> _
<WebBrowsableAttribute(True)> _
<LocalizedWebDescriptionAttribute("AddToCartWebDescriptionShoppingCartPageUrl")> _
Public Property RedirectUrl As String
    Get
    Set
'Usage
Dim instance As AddToCart
Dim value As String

value = instance.RedirectUrl

instance.RedirectUrl = value
```

``` csharp
[LocalizedCategoryAttribute("AddToCartCustomPropertiesSettings")]
[PersonalizableAttribute(PersonalizationScope.Shared)]
[LocalizedWebDisplayNameAttribute("AddToCartWebDisplayNameShoppingCartPageUrl")]
[WebPartStorageAttribute(Storage.Shared)]
[WebBrowsableAttribute(true)]
[LocalizedWebDescriptionAttribute("AddToCartWebDescriptionShoppingCartPageUrl")]
public string RedirectUrl { get; set; }
```

``` c++
[LocalizedCategoryAttribute(L"AddToCartCustomPropertiesSettings")]
[PersonalizableAttribute(PersonalizationScope::Shared)]
[LocalizedWebDisplayNameAttribute(L"AddToCartWebDisplayNameShoppingCartPageUrl")]
[WebPartStorageAttribute(Storage::Shared)]
[WebBrowsableAttribute(true)]
[LocalizedWebDescriptionAttribute(L"AddToCartWebDescriptionShoppingCartPageUrl")]
public:
property String^ RedirectUrl {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[AddToCart Class](addtocart-class-microsoft-dynamics-retail-sharepoint-web-webparts.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.WebParts Namespace](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)

