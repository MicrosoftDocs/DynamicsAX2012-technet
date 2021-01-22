---
title: ControlFactory.CreateLargeButton Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Controls)
TOCTitle: CreateLargeButton Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Controls.ControlFactory.CreateLargeButton(System.Web.UI.HtmlControls.HtmlButton,System.String,System.String,Microsoft.Dynamics.Retail.SharePoint.Web.Controls.ButtonTextAlignment,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.controls.controlfactory.createlargebutton(v=AX.60)
ms:contentKeyID: 62207574
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Controls.ControlFactory.CreateLargeButton
dev_langs:
- CSharp
- C++
- VB
---

# CreateLargeButton Method

Creates a large button.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Controls](microsoft-dynamics-retail-sharepoint-web-controls-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Controls (in Microsoft.Dynamics.Retail.SP.Web.Controls.dll)

## Syntax

``` vb
'Declaration
Public Shared Function CreateLargeButton ( _
    button As HtmlButton, _
    buttonStyle As String, _
    buttonIcon As String, _
    alignment As ButtonTextAlignment, _
    buttonClass As String _
) As Control
'Usage
Dim button As HtmlButton
Dim buttonStyle As String
Dim buttonIcon As String
Dim alignment As ButtonTextAlignment
Dim buttonClass As String
Dim returnValue As Control

returnValue = ControlFactory.CreateLargeButton(button, _
    buttonStyle, buttonIcon, alignment, _
    buttonClass)
```

``` csharp
public static Control CreateLargeButton(
    HtmlButton button,
    string buttonStyle,
    string buttonIcon,
    ButtonTextAlignment alignment,
    string buttonClass
)
```

``` c++
public:
static Control^ CreateLargeButton(
    HtmlButton^ button, 
    String^ buttonStyle, 
    String^ buttonIcon, 
    ButtonTextAlignment alignment, 
    String^ buttonClass
)
```

#### Parameters

  - button  
    Type: [System.Web.UI.HtmlControls.HtmlButton](https://technet.microsoft.com/library/9dy4xy15\(v=ax.60\))  

<!-- end list -->

  - buttonStyle  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - buttonIcon  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - alignment  
    Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Controls.ButtonTextAlignment](buttontextalignment-enumeration-microsoft-dynamics-retail-sharepoint-web-controls.md)  

<!-- end list -->

  - buttonClass  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Web.UI.Control](https://technet.microsoft.com/library/983zwx2h\(v=ax.60\))  
A button instance.  

## See Also

#### Reference

[ControlFactory Class](controlfactory-class-microsoft-dynamics-retail-sharepoint-web-controls.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Controls Namespace](microsoft-dynamics-retail-sharepoint-web-controls-namespace.md)

