---
title: ControlFactory.CreateLabel Method (String, String, HtmlSelect) (Microsoft.Dynamics.Retail.SharePoint.Web.Controls)
TOCTitle: CreateLabel Method (String, String, HtmlSelect)
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Controls.ControlFactory.CreateLabel(System.String,System.String,System.Web.UI.HtmlControls.HtmlSelect)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.controls.controlfactory.createlabel(v=AX.60)
ms:contentKeyID: 62204625
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# CreateLabel Method (String, String, HtmlSelect)

Create a .NET Label control for a SELECT HTML control.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Controls](microsoft-dynamics-retail-sharepoint-web-controls-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Controls (in Microsoft.Dynamics.Retail.SP.Web.Controls.dll)

## Syntax

``` vb
'Declaration
Public Shared Function CreateLabel ( _
    text As String, _
    className As String, _
    associatedControl As HtmlSelect _
) As HtmlLabel
'Usage
Dim text As String
Dim className As String
Dim associatedControl As HtmlSelect
Dim returnValue As HtmlLabel

returnValue = ControlFactory.CreateLabel(text, _
    className, associatedControl)
```

``` csharp
public static HtmlLabel CreateLabel(
    string text,
    string className,
    HtmlSelect associatedControl
)
```

``` c++
public:
static HtmlLabel^ CreateLabel(
    String^ text, 
    String^ className, 
    HtmlSelect^ associatedControl
)
```

#### Parameters

  - text  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - className  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - associatedControl  
    Type: [System.Web.UI.HtmlControls.HtmlSelect](https://technet.microsoft.com/library/xf11z4ad\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Controls.HtmlControls.HtmlLabel](htmllabel-class-microsoft-dynamics-retail-sharepoint-web-controls-htmlcontrols.md)  
A label instance.  

## See Also

#### Reference

[ControlFactory Class](controlfactory-class-microsoft-dynamics-retail-sharepoint-web-controls.md)

[CreateLabel Overload](controlfactory-createlabel-method-microsoft-dynamics-retail-sharepoint-web-controls.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Controls Namespace](microsoft-dynamics-retail-sharepoint-web-controls-namespace.md)

