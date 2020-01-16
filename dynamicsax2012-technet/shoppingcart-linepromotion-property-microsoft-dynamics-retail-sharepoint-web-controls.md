---
title: ShoppingCart.LinePromotion Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Controls)
TOCTitle: LinePromotion Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Controls.ShoppingCart.LinePromotion
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.controls.shoppingcart.linepromotion(v=AX.60)
ms:contentKeyID: 62202922
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Controls.ShoppingCart.LinePromotion
dev_langs:
- CSharp
- C++
- VB
---

# LinePromotion Property

Gets or sets the line promotion.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Controls](microsoft-dynamics-retail-sharepoint-web-controls-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Controls (in Microsoft.Dynamics.Retail.SP.Web.Controls.dll)

## Syntax

``` vb
'Declaration
Protected Property LinePromotion As HtmlTableRow
    Get
    Set
'Usage
Dim value As HtmlTableRow

value = Me.LinePromotion

Me.LinePromotion = value
```

``` csharp
protected HtmlTableRow LinePromotion { get; set; }
```

``` c++
protected:
property HtmlTableRow^ LinePromotion {
    HtmlTableRow^ get ();
    void set (HtmlTableRow^ value);
}
```

#### Property Value

Type: [System.Web.UI.HtmlControls.HtmlTableRow](https://technet.microsoft.com/library/3x5s86zd\(v=ax.60\))  
The line promotion.  

## See Also

#### Reference

[ShoppingCart Class](shoppingcart-class-microsoft-dynamics-retail-sharepoint-web-controls.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Controls Namespace](microsoft-dynamics-retail-sharepoint-web-controls-namespace.md)

