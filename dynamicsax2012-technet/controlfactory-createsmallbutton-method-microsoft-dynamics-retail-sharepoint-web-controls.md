---
title: ControlFactory.CreateSmallButton Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Controls)
TOCTitle: CreateSmallButton Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Controls.ControlFactory.CreateSmallButton(System.Web.UI.HtmlControls.HtmlButton,System.String,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.controls.controlfactory.createsmallbutton(v=AX.60)
ms:contentKeyID: 62203128
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Controls.ControlFactory.CreateSmallButton
dev_langs:
- CSharp
- C++
- VB
---

# CreateSmallButton Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Creates a small button.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Controls](microsoft-dynamics-retail-sharepoint-web-controls-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Controls (in Microsoft.Dynamics.Retail.SP.Web.Controls.dll)

## Syntax

``` vb
'Declaration
Public Shared Function CreateSmallButton ( _
    button As HtmlButton, _
    buttonStyle As String, _
    buttonIcon As String, _
    buttonClass As String _
) As Control
'Usage
Dim button As HtmlButton
Dim buttonStyle As String
Dim buttonIcon As String
Dim buttonClass As String
Dim returnValue As Control

returnValue = ControlFactory.CreateSmallButton(button, _
    buttonStyle, buttonIcon, buttonClass)
```

``` csharp
public static Control CreateSmallButton(
    HtmlButton button,
    string buttonStyle,
    string buttonIcon,
    string buttonClass
)
```

``` c++
public:
static Control^ CreateSmallButton(
    HtmlButton^ button, 
    String^ buttonStyle, 
    String^ buttonIcon, 
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

  - buttonClass  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Web.UI.Control](https://technet.microsoft.com/library/983zwx2h\(v=ax.60\))  
A button instance.  

## See Also

#### Reference

[ControlFactory Class](controlfactory-class-microsoft-dynamics-retail-sharepoint-web-controls.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Controls Namespace](microsoft-dynamics-retail-sharepoint-web-controls-namespace.md)

