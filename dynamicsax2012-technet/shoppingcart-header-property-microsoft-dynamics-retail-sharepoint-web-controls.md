---
title: ShoppingCart.Header Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Controls)
TOCTitle: Header Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Controls.ShoppingCart.Header
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.controls.shoppingcart.header(v=AX.60)
ms:contentKeyID: 62207603
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Controls.ShoppingCart.Header
dev_langs:
- CSharp
- C++
- VB
---

# Header Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the header.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Controls](microsoft-dynamics-retail-sharepoint-web-controls-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Controls (in Microsoft.Dynamics.Retail.SP.Web.Controls.dll)

## Syntax

``` vb
'Declaration
Protected Property Header As HtmlTableRow
    Get
    Set
'Usage
Dim value As HtmlTableRow

value = Me.Header

Me.Header = value
```

``` csharp
protected HtmlTableRow Header { get; set; }
```

``` c++
protected:
property HtmlTableRow^ Header {
    HtmlTableRow^ get ();
    void set (HtmlTableRow^ value);
}
```

#### Property Value

Type: [System.Web.UI.HtmlControls.HtmlTableRow](https://technet.microsoft.com/library/3x5s86zd\(v=ax.60\))  
The header.  

## See Also

#### Reference

[ShoppingCart Class](shoppingcart-class-microsoft-dynamics-retail-sharepoint-web-controls.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Controls Namespace](microsoft-dynamics-retail-sharepoint-web-controls-namespace.md)

