---
title: ControlFactory.CreateCheckBox Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Controls)
TOCTitle: CreateCheckBox Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Controls.ControlFactory.CreateCheckBox(System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.web.controls.controlfactory.createcheckbox(v=AX.60)
ms:contentKeyID: 62206426
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Controls.ControlFactory.CreateCheckBox
dev_langs:
- CSharp
- C++
- VB
---

# CreateCheckBox Method

Create a .NET Checkbox control.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Controls](microsoft-dynamics-retail-sharepoint-web-controls-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Controls (in Microsoft.Dynamics.Retail.SP.Web.Controls.dll)

## Syntax

``` vb
'Declaration
Public Shared Function CreateCheckBox ( _
    className As String _
) As HtmlInputCheckBox
'Usage
Dim className As String
Dim returnValue As HtmlInputCheckBox

returnValue = ControlFactory.CreateCheckBox(className)
```

``` csharp
public static HtmlInputCheckBox CreateCheckBox(
    string className
)
```

``` c++
public:
static HtmlInputCheckBox^ CreateCheckBox(
    String^ className
)
```

#### Parameters

  - className  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Web.UI.HtmlControls.HtmlInputCheckBox](https://technet.microsoft.com/en-us/library/a2x9285k\(v=ax.60\))  
A checkbox instance.  

## See Also

#### Reference

[ControlFactory Class](controlfactory-class-microsoft-dynamics-retail-sharepoint-web-controls.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Controls Namespace](microsoft-dynamics-retail-sharepoint-web-controls-namespace.md)

