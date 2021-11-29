---
title: AddToCart.RedirectUrl Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Controls)
TOCTitle: RedirectUrl Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Controls.AddToCart.RedirectUrl
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.controls.addtocart.redirecturl(v=AX.60)
ms:contentKeyID: 62206983
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Controls.AddToCart.RedirectUrl
dev_langs:
- CSharp
- C++
- VB
---

# RedirectUrl Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the page to redirect to after adding an item to the cart. Empty Url means no redirect.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Controls](microsoft-dynamics-retail-sharepoint-web-controls-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Controls (in Microsoft.Dynamics.Retail.SP.Web.Controls.dll)

## Syntax

``` vb
'Declaration
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
public string RedirectUrl { get; set; }
```

``` c++
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

[AddToCart Class](addtocart-class-microsoft-dynamics-retail-sharepoint-web-controls.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Controls Namespace](microsoft-dynamics-retail-sharepoint-web-controls-namespace.md)

