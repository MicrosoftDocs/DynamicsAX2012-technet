---
title: ControlFactory.CreateHiddenInput Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Controls)
TOCTitle: CreateHiddenInput Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Controls.ControlFactory.CreateHiddenInput(System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.web.controls.controlfactory.createhiddeninput(v=AX.60)
ms:contentKeyID: 62204654
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Controls.ControlFactory.CreateHiddenInput
dev_langs:
- CSharp
- C++
- VB
---

# CreateHiddenInput Method

Create a .NET HTML Hidden Input control.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Controls](microsoft-dynamics-retail-sharepoint-web-controls-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Controls (in Microsoft.Dynamics.Retail.SP.Web.Controls.dll)

## Syntax

``` vb
'Declaration
Public Shared Function CreateHiddenInput ( _
    value As String, _
    className As String _
) As HtmlInputHidden
'Usage
Dim value As String
Dim className As String
Dim returnValue As HtmlInputHidden

returnValue = ControlFactory.CreateHiddenInput(value, _
    className)
```

``` csharp
public static HtmlInputHidden CreateHiddenInput(
    string value,
    string className
)
```

``` c++
public:
static HtmlInputHidden^ CreateHiddenInput(
    String^ value, 
    String^ className
)
```

#### Parameters

  - value  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - className  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Web.UI.HtmlControls.HtmlInputHidden](https://technet.microsoft.com/en-us/library/x2sy02b0\(v=ax.60\))  
An HtmlInputHidden instance.  

## See Also

#### Reference

[ControlFactory Class](controlfactory-class-microsoft-dynamics-retail-sharepoint-web-controls.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Controls Namespace](microsoft-dynamics-retail-sharepoint-web-controls-namespace.md)

