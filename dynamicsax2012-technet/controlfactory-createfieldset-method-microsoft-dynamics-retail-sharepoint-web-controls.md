---
title: ControlFactory.CreateFieldSet Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Controls)
TOCTitle: CreateFieldSet Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Controls.ControlFactory.CreateFieldSet(System.String[])
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.controls.controlfactory.createfieldset(v=AX.60)
ms:contentKeyID: 62205817
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Controls.ControlFactory.CreateFieldSet
dev_langs:
- CSharp
- C++
- VB
---

# CreateFieldSet Method

Creates a fieldset element (fieldset) for grouping controls.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Controls](microsoft-dynamics-retail-sharepoint-web-controls-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Controls (in Microsoft.Dynamics.Retail.SP.Web.Controls.dll)

## Syntax

``` vb
'Declaration
Public Shared Function CreateFieldSet ( _
    ParamArray classNames As String() _
) As HtmlFieldSet
'Usage
Dim classNames As String()
Dim returnValue As HtmlFieldSet

returnValue = ControlFactory.CreateFieldSet(classNames)
```

``` csharp
public static HtmlFieldSet CreateFieldSet(
    params string[] classNames
)
```

``` c++
public:
static HtmlFieldSet^ CreateFieldSet(
    ... array<String^>^ classNames
)
```

#### Parameters

  - classNames  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\[\]  

#### Return Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Controls.HtmlControls.HtmlFieldSet](htmlfieldset-class-microsoft-dynamics-retail-sharepoint-web-controls-htmlcontrols.md)  
A HtmlFieldSet element containing the text to display.  

## See Also

#### Reference

[ControlFactory Class](controlfactory-class-microsoft-dynamics-retail-sharepoint-web-controls.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Controls Namespace](microsoft-dynamics-retail-sharepoint-web-controls-namespace.md)

