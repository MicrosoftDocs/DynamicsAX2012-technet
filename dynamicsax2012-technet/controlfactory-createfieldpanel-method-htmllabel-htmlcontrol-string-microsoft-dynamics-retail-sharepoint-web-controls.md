---
title: ControlFactory.CreateFieldPanel Method (HtmlLabel, HtmlControl, String) (Microsoft.Dynamics.Retail.SharePoint.Web.Controls)
TOCTitle: CreateFieldPanel Method (HtmlLabel, HtmlControl, String)
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Controls.ControlFactory.CreateFieldPanel(Microsoft.Dynamics.Retail.SharePoint.Web.Controls.HtmlControls.HtmlLabel,System.Web.UI.HtmlControls.HtmlControl,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.controls.controlfactory.createfieldpanel(v=AX.60)
ms:contentKeyID: 62202998
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# CreateFieldPanel Method (HtmlLabel, HtmlControl, String)

Create a panel containing a label associated with an input control with label first.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Controls](microsoft-dynamics-retail-sharepoint-web-controls-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Controls (in Microsoft.Dynamics.Retail.SP.Web.Controls.dll)

## Syntax

``` vb
'Declaration
Public Shared Function CreateFieldPanel ( _
    label As HtmlLabel, _
    field As HtmlControl, _
    className As String _
) As HtmlFieldPanel
'Usage
Dim label As HtmlLabel
Dim field As HtmlControl
Dim className As String
Dim returnValue As HtmlFieldPanel

returnValue = ControlFactory.CreateFieldPanel(label, _
    field, className)
```

``` csharp
public static HtmlFieldPanel CreateFieldPanel(
    HtmlLabel label,
    HtmlControl field,
    string className
)
```

``` c++
public:
static HtmlFieldPanel^ CreateFieldPanel(
    HtmlLabel^ label, 
    HtmlControl^ field, 
    String^ className
)
```

#### Parameters

  - label  
    Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Controls.HtmlControls.HtmlLabel](htmllabel-class-microsoft-dynamics-retail-sharepoint-web-controls-htmlcontrols.md)  

<!-- end list -->

  - field  
    Type: [System.Web.UI.HtmlControls.HtmlControl](https://technet.microsoft.com/library/khc6t495\(v=ax.60\))  

<!-- end list -->

  - className  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Controls.HtmlControls.HtmlFieldPanel](htmlfieldpanel-class-microsoft-dynamics-retail-sharepoint-web-controls-htmlcontrols.md)  
A panel instance containing the label and input controls.  

## Remarks

A Panel renders as a Div element.

## See Also

#### Reference

[ControlFactory Class](controlfactory-class-microsoft-dynamics-retail-sharepoint-web-controls.md)

[CreateFieldPanel Overload](controlfactory-createfieldpanel-method-microsoft-dynamics-retail-sharepoint-web-controls.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Controls Namespace](microsoft-dynamics-retail-sharepoint-web-controls-namespace.md)

