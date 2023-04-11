---
title: AddToCart.ListingIdSelector Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Controls)
TOCTitle: ListingIdSelector Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Controls.AddToCart.ListingIdSelector
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.controls.addtocart.listingidselector(v=AX.60)
ms:contentKeyID: 62206760
author: tfehr
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Controls.AddToCart.ListingIdSelector
dev_langs:
- CSharp
- C++
- VB
---

# ListingIdSelector Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the jQuery selector to use to obtain the listingId from the page.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Controls](microsoft-dynamics-retail-sharepoint-web-controls-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Controls (in Microsoft.Dynamics.Retail.SP.Web.Controls.dll)

## Syntax

``` vb
'Declaration
Public Property ListingIdSelector As String
    Get
    Set
'Usage
Dim instance As AddToCart
Dim value As String

value = instance.ListingIdSelector

instance.ListingIdSelector = value
```

``` csharp
public string ListingIdSelector { get; set; }
```

``` c++
public:
property String^ ListingIdSelector {
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

