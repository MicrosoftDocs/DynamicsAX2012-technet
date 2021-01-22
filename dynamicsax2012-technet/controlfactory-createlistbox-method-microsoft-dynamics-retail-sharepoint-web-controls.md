---
title: ControlFactory.CreateListBox Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Controls)
TOCTitle: CreateListBox Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Controls.ControlFactory.CreateListBox(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.controls.controlfactory.createlistbox(v=AX.60)
ms:contentKeyID: 62202384
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Controls.ControlFactory.CreateListBox
dev_langs:
- CSharp
- C++
- VB
---

# CreateListBox Method

Create a .NET DropDown control.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Controls](microsoft-dynamics-retail-sharepoint-web-controls-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Controls (in Microsoft.Dynamics.Retail.SP.Web.Controls.dll)

## Syntax

``` vb
'Declaration
Public Shared Function CreateListBox ( _
    className As String _
) As HtmlSelect
'Usage
Dim className As String
Dim returnValue As HtmlSelect

returnValue = ControlFactory.CreateListBox(className)
```

``` csharp
public static HtmlSelect CreateListBox(
    string className
)
```

``` c++
public:
static HtmlSelect^ CreateListBox(
    String^ className
)
```

#### Parameters

  - className  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Web.UI.HtmlControls.HtmlSelect](https://technet.microsoft.com/library/xf11z4ad\(v=ax.60\))  
An HtmlSelect instance.  

## See Also

#### Reference

[ControlFactory Class](controlfactory-class-microsoft-dynamics-retail-sharepoint-web-controls.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Controls Namespace](microsoft-dynamics-retail-sharepoint-web-controls-namespace.md)

