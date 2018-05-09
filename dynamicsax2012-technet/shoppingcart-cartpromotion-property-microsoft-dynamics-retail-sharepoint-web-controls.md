---
title: ShoppingCart.CartPromotion Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Controls)
TOCTitle: CartPromotion Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Controls.ShoppingCart.CartPromotion
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.web.controls.shoppingcart.cartpromotion(v=AX.60)
ms:contentKeyID: 62204313
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Controls.ShoppingCart.CartPromotion
dev_langs:
- CSharp
- C++
- VB
---

# CartPromotion Property

Gets or sets the cart promotion.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Controls](microsoft-dynamics-retail-sharepoint-web-controls-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Controls (in Microsoft.Dynamics.Retail.SP.Web.Controls.dll)

## Syntax

``` vb
'Declaration
Protected Property CartPromotion As HtmlDiv
    Get
    Set
'Usage
Dim value As HtmlDiv

value = Me.CartPromotion

Me.CartPromotion = value
```

``` csharp
protected HtmlDiv CartPromotion { get; set; }
```

``` c++
protected:
property HtmlDiv^ CartPromotion {
    HtmlDiv^ get ();
    void set (HtmlDiv^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Controls.HtmlControls.HtmlDiv](htmldiv-class-microsoft-dynamics-retail-sharepoint-web-controls-htmlcontrols.md)  
The cart promotion.  

## See Also

#### Reference

[ShoppingCart Class](shoppingcart-class-microsoft-dynamics-retail-sharepoint-web-controls.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Controls Namespace](microsoft-dynamics-retail-sharepoint-web-controls-namespace.md)

