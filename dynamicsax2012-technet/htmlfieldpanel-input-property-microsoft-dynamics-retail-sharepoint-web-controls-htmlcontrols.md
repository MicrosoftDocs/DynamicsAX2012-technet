---
title: HtmlFieldPanel.Input Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Controls.HtmlControls)
TOCTitle: Input Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Controls.HtmlControls.HtmlFieldPanel.Input
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.controls.htmlcontrols.htmlfieldpanel.input(v=AX.60)
ms:contentKeyID: 62205843
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Controls.HtmlControls.HtmlFieldPanel.Input
dev_langs:
- CSharp
- C++
- VB
---

# Input Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the input control associated with the label.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Controls.HtmlControls](microsoft-dynamics-retail-sharepoint-web-controls-htmlcontrols-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Controls (in Microsoft.Dynamics.Retail.SP.Web.Controls.dll)

## Syntax

``` vb
'Declaration
Public Property Input As HtmlControl
    Get
    Set
'Usage
Dim instance As HtmlFieldPanel
Dim value As HtmlControl

value = instance.Input

instance.Input = value
```

``` csharp
public HtmlControl Input { get; set; }
```

``` c++
public:
property HtmlControl^ Input {
    HtmlControl^ get ();
    void set (HtmlControl^ value);
}
```

#### Property Value

Type: [System.Web.UI.HtmlControls.HtmlControl](https://technet.microsoft.com/library/khc6t495\(v=ax.60\))  
Returns [HtmlControl](https://technet.microsoft.com/library/khc6t495\(v=ax.60\)).  

## See Also

#### Reference

[HtmlFieldPanel Class](htmlfieldpanel-class-microsoft-dynamics-retail-sharepoint-web-controls-htmlcontrols.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Controls.HtmlControls Namespace](microsoft-dynamics-retail-sharepoint-web-controls-htmlcontrols-namespace.md)

