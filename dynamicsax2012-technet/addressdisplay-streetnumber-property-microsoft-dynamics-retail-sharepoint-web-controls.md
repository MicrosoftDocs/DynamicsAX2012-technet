---
title: AddressDisplay.StreetNumber Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Controls)
TOCTitle: StreetNumber Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Controls.AddressDisplay.StreetNumber
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.controls.addressdisplay.streetnumber(v=AX.60)
ms:contentKeyID: 62206252
author: tonyafehr
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Controls.AddressDisplay.StreetNumber
dev_langs:
- CSharp
- C++
- VB
---

# StreetNumber Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the StreetNumber.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Controls](microsoft-dynamics-retail-sharepoint-web-controls-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Controls (in Microsoft.Dynamics.Retail.SP.Web.Controls.dll)

## Syntax

``` vb
'Declaration
Public Property StreetNumber As HtmlSpan
    Get
    Private Set
'Usage
Dim instance As AddressDisplay
Dim value As HtmlSpan

value = instance.StreetNumber
```

``` csharp
public HtmlSpan StreetNumber { get; private set; }
```

``` c++
public:
property HtmlSpan^ StreetNumber {
    HtmlSpan^ get ();
    private: void set (HtmlSpan^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Controls.HtmlControls.HtmlSpan](htmlspan-class-microsoft-dynamics-retail-sharepoint-web-controls-htmlcontrols.md)  
Returns [HtmlSpan](htmlspan-class-microsoft-dynamics-retail-sharepoint-web-controls-htmlcontrols.md).  

## See Also

#### Reference

[AddressDisplay Class](addressdisplay-class-microsoft-dynamics-retail-sharepoint-web-controls.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Controls Namespace](microsoft-dynamics-retail-sharepoint-web-controls-namespace.md)

