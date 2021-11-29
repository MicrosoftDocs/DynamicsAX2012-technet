---
title: ShoppingCart.KitComponents Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Controls)
TOCTitle: KitComponents Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Controls.ShoppingCart.KitComponents
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.controls.shoppingcart.kitcomponents(v=AX.60)
ms:contentKeyID: 62202725
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Controls.ShoppingCart.KitComponents
dev_langs:
- CSharp
- C++
- VB
---

# KitComponents Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the kit components.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Controls](microsoft-dynamics-retail-sharepoint-web-controls-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Controls (in Microsoft.Dynamics.Retail.SP.Web.Controls.dll)

## Syntax

``` vb
'Declaration
Protected Property KitComponents As HtmlTableRow
    Get
    Set
'Usage
Dim value As HtmlTableRow

value = Me.KitComponents

Me.KitComponents = value
```

``` csharp
protected HtmlTableRow KitComponents { get; set; }
```

``` c++
protected:
property HtmlTableRow^ KitComponents {
    HtmlTableRow^ get ();
    void set (HtmlTableRow^ value);
}
```

#### Property Value

Type: [System.Web.UI.HtmlControls.HtmlTableRow](https://technet.microsoft.com/library/3x5s86zd\(v=ax.60\))  
The kit components.  

## See Also

#### Reference

[ShoppingCart Class](shoppingcart-class-microsoft-dynamics-retail-sharepoint-web-controls.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Controls Namespace](microsoft-dynamics-retail-sharepoint-web-controls-namespace.md)

