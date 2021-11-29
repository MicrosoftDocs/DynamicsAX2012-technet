---
title: ControlFactory.CreateAnchor Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Controls)
TOCTitle: CreateAnchor Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Controls.ControlFactory.CreateAnchor(System.String,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.controls.controlfactory.createanchor(v=AX.60)
ms:contentKeyID: 62201909
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Controls.ControlFactory.CreateAnchor
dev_langs:
- CSharp
- C++
- VB
---

# CreateAnchor Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Create a .NET Anchor control.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Controls](microsoft-dynamics-retail-sharepoint-web-controls-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Controls (in Microsoft.Dynamics.Retail.SP.Web.Controls.dll)

## Syntax

``` vb
'Declaration
Public Shared Function CreateAnchor ( _
    text As String, _
    url As String, _
    className As String _
) As HtmlAnchor
'Usage
Dim text As String
Dim url As String
Dim className As String
Dim returnValue As HtmlAnchor

returnValue = ControlFactory.CreateAnchor(text, _
    url, className)
```

``` csharp
public static HtmlAnchor CreateAnchor(
    string text,
    string url,
    string className
)
```

``` c++
public:
static HtmlAnchor^ CreateAnchor(
    String^ text, 
    String^ url, 
    String^ className
)
```

#### Parameters

  - text  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - url  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - className  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Web.UI.HtmlControls.HtmlAnchor](https://technet.microsoft.com/library/3ef7c738\(v=ax.60\))  
An anchor instance.  

## See Also

#### Reference

[ControlFactory Class](controlfactory-class-microsoft-dynamics-retail-sharepoint-web-controls.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Controls Namespace](microsoft-dynamics-retail-sharepoint-web-controls-namespace.md)

