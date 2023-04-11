---
title: MiniShoppingCart.ShoppingCartUrl Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Controls)
TOCTitle: ShoppingCartUrl Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Controls.MiniShoppingCart.ShoppingCartUrl
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.controls.minishoppingcart.shoppingcarturl(v=AX.60)
ms:contentKeyID: 62205215
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Controls.MiniShoppingCart.ShoppingCartUrl
dev_langs:
- CSharp
- C++
- VB
---

# ShoppingCartUrl Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the redirect URL to the shopping cart. If omitted, no redirect happens.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Controls](microsoft-dynamics-retail-sharepoint-web-controls-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Controls (in Microsoft.Dynamics.Retail.SP.Web.Controls.dll)

## Syntax

``` vb
'Declaration
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
public string ShoppingCartUrl { get; set; }
```

``` c++
public:
property String^ ShoppingCartUrl {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[MiniShoppingCart Class](minishoppingcart-class-microsoft-dynamics-retail-sharepoint-web-controls.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Controls Namespace](microsoft-dynamics-retail-sharepoint-web-controls-namespace.md)

