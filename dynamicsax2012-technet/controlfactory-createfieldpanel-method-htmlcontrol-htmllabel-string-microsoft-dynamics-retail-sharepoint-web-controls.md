---
title: ControlFactory.CreateFieldPanel Method (HtmlControl, HtmlLabel, String) (Microsoft.Dynamics.Retail.SharePoint.Web.Controls)
TOCTitle: CreateFieldPanel Method (HtmlControl, HtmlLabel, String)
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Controls.ControlFactory.CreateFieldPanel(System.Web.UI.HtmlControls.HtmlControl,Microsoft.Dynamics.Retail.SharePoint.Web.Controls.HtmlControls.HtmlLabel,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.controls.controlfactory.createfieldpanel(v=AX.60)
ms:contentKeyID: 62203890
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# CreateFieldPanel Method (HtmlControl, HtmlLabel, String)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Create a panel containing a label associated with an input control with label last.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Controls](microsoft-dynamics-retail-sharepoint-web-controls-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Controls (in Microsoft.Dynamics.Retail.SP.Web.Controls.dll)

## Syntax

``` vb
'Declaration
Public Shared Function CreateFieldPanel ( _
    field As HtmlControl, _
    label As HtmlLabel, _
    className As String _
) As HtmlFieldPanel
'Usage
Dim field As HtmlControl
Dim label As HtmlLabel
Dim className As String
Dim returnValue As HtmlFieldPanel

returnValue = ControlFactory.CreateFieldPanel(field, _
    label, className)
```

``` csharp
public static HtmlFieldPanel CreateFieldPanel(
    HtmlControl field,
    HtmlLabel label,
    string className
)
```

``` c++
public:
static HtmlFieldPanel^ CreateFieldPanel(
    HtmlControl^ field, 
    HtmlLabel^ label, 
    String^ className
)
```

#### Parameters

  - field  
    Type: [System.Web.UI.HtmlControls.HtmlControl](https://technet.microsoft.com/library/khc6t495\(v=ax.60\))  

<!-- end list -->

  - label  
    Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Controls.HtmlControls.HtmlLabel](htmllabel-class-microsoft-dynamics-retail-sharepoint-web-controls-htmlcontrols.md)  

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

