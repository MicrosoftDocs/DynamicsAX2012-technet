---
title: ControlFactory.CreateParagraph Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Controls)
TOCTitle: CreateParagraph Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Controls.ControlFactory.CreateParagraph(System.String[])
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.controls.controlfactory.createparagraph(v=AX.60)
ms:contentKeyID: 62206679
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Controls.ControlFactory.CreateParagraph
dev_langs:
- CSharp
- C++
- VB
---

# CreateParagraph Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Creates a paragraph element (p) for inserting text.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Controls](microsoft-dynamics-retail-sharepoint-web-controls-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Controls (in Microsoft.Dynamics.Retail.SP.Web.Controls.dll)

## Syntax

``` vb
'Declaration
Public Shared Function CreateParagraph ( _
    ParamArray classNames As String() _
) As HtmlParagraph
'Usage
Dim classNames As String()
Dim returnValue As HtmlParagraph

returnValue = ControlFactory.CreateParagraph(classNames)
```

``` csharp
public static HtmlParagraph CreateParagraph(
    params string[] classNames
)
```

``` c++
public:
static HtmlParagraph^ CreateParagraph(
    ... array<String^>^ classNames
)
```

#### Parameters

  - classNames  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\[\]  

#### Return Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Controls.HtmlControls.HtmlParagraph](htmlparagraph-class-microsoft-dynamics-retail-sharepoint-web-controls-htmlcontrols.md)  
A HtmlParagraph element containing the text to display.  

## See Also

#### Reference

[ControlFactory Class](controlfactory-class-microsoft-dynamics-retail-sharepoint-web-controls.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Controls Namespace](microsoft-dynamics-retail-sharepoint-web-controls-namespace.md)

