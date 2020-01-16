---
title: ControlFactory.CreatePasswordTextBox Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Controls)
TOCTitle: CreatePasswordTextBox Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Controls.ControlFactory.CreatePasswordTextBox(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.controls.controlfactory.createpasswordtextbox(v=AX.60)
ms:contentKeyID: 62207675
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Controls.ControlFactory.CreatePasswordTextBox
dev_langs:
- CSharp
- C++
- VB
---

# CreatePasswordTextBox Method

Create a .NET Password Text Box control.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Controls](microsoft-dynamics-retail-sharepoint-web-controls-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Controls (in Microsoft.Dynamics.Retail.SP.Web.Controls.dll)

## Syntax

``` vb
'Declaration
Public Shared Function CreatePasswordTextBox ( _
    className As String _
) As HtmlInputPassword
'Usage
Dim className As String
Dim returnValue As HtmlInputPassword

returnValue = ControlFactory.CreatePasswordTextBox(className)
```

``` csharp
public static HtmlInputPassword CreatePasswordTextBox(
    string className
)
```

``` c++
public:
static HtmlInputPassword^ CreatePasswordTextBox(
    String^ className
)
```

#### Parameters

  - className  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Web.UI.HtmlControls.HtmlInputPassword](https://technet.microsoft.com/library/4c132kk7\(v=ax.60\))  
A password text box instance.  

## See Also

#### Reference

[ControlFactory Class](controlfactory-class-microsoft-dynamics-retail-sharepoint-web-controls.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Controls Namespace](microsoft-dynamics-retail-sharepoint-web-controls-namespace.md)

