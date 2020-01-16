---
title: ControlFactory.CreateOption Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Controls)
TOCTitle: CreateOption Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Controls.ControlFactory.CreateOption(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.controls.controlfactory.createoption(v=AX.60)
ms:contentKeyID: 62204889
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Controls.ControlFactory.CreateOption
dev_langs:
- CSharp
- C++
- VB
---

# CreateOption Method

Creates an option to be used by the [HtmlSelect](https://technet.microsoft.com/library/xf11z4ad\(v=ax.60\)) element.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Controls](microsoft-dynamics-retail-sharepoint-web-controls-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Controls (in Microsoft.Dynamics.Retail.SP.Web.Controls.dll)

## Syntax

``` vb
'Declaration
Public Shared Function CreateOption ( _
    className As String _
) As ListItem
'Usage
Dim className As String
Dim returnValue As ListItem

returnValue = ControlFactory.CreateOption(className)
```

``` csharp
public static ListItem CreateOption(
    string className
)
```

``` c++
public:
static ListItem^ CreateOption(
    String^ className
)
```

#### Parameters

  - className  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Web.UI.WebControls.ListItem](https://technet.microsoft.com/library/bb768tf6\(v=ax.60\))  
A HtmlSelectOption element containing the text and value to display.  

## See Also

#### Reference

[ControlFactory Class](controlfactory-class-microsoft-dynamics-retail-sharepoint-web-controls.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Controls Namespace](microsoft-dynamics-retail-sharepoint-web-controls-namespace.md)

