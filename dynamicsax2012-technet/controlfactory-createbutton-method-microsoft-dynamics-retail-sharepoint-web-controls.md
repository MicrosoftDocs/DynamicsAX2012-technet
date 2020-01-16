---
title: ControlFactory.CreateButton Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Controls)
TOCTitle: CreateButton Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Controls.ControlFactory.CreateButton(System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.controls.controlfactory.createbutton(v=AX.60)
ms:contentKeyID: 62206090
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Controls.ControlFactory.CreateButton
dev_langs:
- CSharp
- C++
- VB
---

# CreateButton Method

Create a .NET Button control.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Controls](microsoft-dynamics-retail-sharepoint-web-controls-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Controls (in Microsoft.Dynamics.Retail.SP.Web.Controls.dll)

## Syntax

``` vb
'Declaration
Public Shared Function CreateButton ( _
    text As String, _
    className As String _
) As HtmlButton
'Usage
Dim text As String
Dim className As String
Dim returnValue As HtmlButton

returnValue = ControlFactory.CreateButton(text, _
    className)
```

``` csharp
public static HtmlButton CreateButton(
    string text,
    string className
)
```

``` c++
public:
static HtmlButton^ CreateButton(
    String^ text, 
    String^ className
)
```

#### Parameters

  - text  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - className  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Web.UI.HtmlControls.HtmlButton](https://technet.microsoft.com/library/9dy4xy15\(v=ax.60\))  
A Button instance.  

## See Also

#### Reference

[ControlFactory Class](controlfactory-class-microsoft-dynamics-retail-sharepoint-web-controls.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Controls Namespace](microsoft-dynamics-retail-sharepoint-web-controls-namespace.md)

