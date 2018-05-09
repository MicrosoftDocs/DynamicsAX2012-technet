---
title: MiniShoppingCart.ShoppingCartUrl Property  (Microsoft.Dynamics.Retail.SharePoint.Web.WebParts)
TOCTitle: ShoppingCartUrl Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.MiniShoppingCart.ShoppingCartUrl
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.web.webparts.minishoppingcart.shoppingcarturl(v=AX.60)
ms:contentKeyID: 62204088
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.MiniShoppingCart.ShoppingCartUrl
dev_langs:
- CSharp
- C++
- VB
---

# ShoppingCartUrl Property

Gets or sets the Url of the mini cart.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.WebParts](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.WebParts (in Microsoft.Dynamics.Retail.SP.Web.WebParts.dll)

## Syntax

``` vb
'Declaration
<PersonalizableAttribute(PersonalizationScope.Shared)> _
<WebPartStorageAttribute(Storage.Shared)> _
<LocalizedWebDisplayNameAttribute("MiniShoppingCartWebDisplayNameShoppingCartUrl")> _
<LocalizedWebDescriptionAttribute("MiniShoppingCartWebDescriptionShoppingCartUrl")> _
<WebBrowsableAttribute(True)> _
<LocalizedCategoryAttribute("MiniShoppingCartCustomPropertiesCategoryName")> _
Public Property ShoppingCartUrl As String
    Get
    Set
'Usage
Dim instance As MiniShoppingCart
Dim value As String

value = instance.ShoppingCartUrl

instance.ShoppingCartUrl = value
```

``` csharp
[PersonalizableAttribute(PersonalizationScope.Shared)]
[WebPartStorageAttribute(Storage.Shared)]
[LocalizedWebDisplayNameAttribute("MiniShoppingCartWebDisplayNameShoppingCartUrl")]
[LocalizedWebDescriptionAttribute("MiniShoppingCartWebDescriptionShoppingCartUrl")]
[WebBrowsableAttribute(true)]
[LocalizedCategoryAttribute("MiniShoppingCartCustomPropertiesCategoryName")]
public string ShoppingCartUrl { get; set; }
```

``` c++
[PersonalizableAttribute(PersonalizationScope::Shared)]
[WebPartStorageAttribute(Storage::Shared)]
[LocalizedWebDisplayNameAttribute(L"MiniShoppingCartWebDisplayNameShoppingCartUrl")]
[LocalizedWebDescriptionAttribute(L"MiniShoppingCartWebDescriptionShoppingCartUrl")]
[WebBrowsableAttribute(true)]
[LocalizedCategoryAttribute(L"MiniShoppingCartCustomPropertiesCategoryName")]
public:
property String^ ShoppingCartUrl {
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

