---
title: ControlFactory.CreateDiv Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Controls)
TOCTitle: CreateDiv Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Controls.ControlFactory.CreateDiv(System.String[])
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.controls.controlfactory.creatediv(v=AX.60)
ms:contentKeyID: 62205662
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Controls.ControlFactory.CreateDiv
dev_langs:
- CSharp
- C++
- VB
---

# CreateDiv Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Creates a division element (div) for adding display controls.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Controls](microsoft-dynamics-retail-sharepoint-web-controls-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Controls (in Microsoft.Dynamics.Retail.SP.Web.Controls.dll)

## Syntax

``` vb
'Declaration
Public Shared Function CreateDiv ( _
    ParamArray classNames As String() _
) As HtmlDiv
'Usage
Dim classNames As String()
Dim returnValue As HtmlDiv

returnValue = ControlFactory.CreateDiv(classNames)
```

``` csharp
public static HtmlDiv CreateDiv(
    params string[] classNames
)
```

``` c++
public:
static HtmlDiv^ CreateDiv(
    ... array<String^>^ classNames
)
```

#### Parameters

  - classNames  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\[\]  

#### Return Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Controls.HtmlControls.HtmlDiv](htmldiv-class-microsoft-dynamics-retail-sharepoint-web-controls-htmlcontrols.md)  
A HtmlDiv element containing the text to display.  

## See Also

#### Reference

[ControlFactory Class](controlfactory-class-microsoft-dynamics-retail-sharepoint-web-controls.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Controls Namespace](microsoft-dynamics-retail-sharepoint-web-controls-namespace.md)

