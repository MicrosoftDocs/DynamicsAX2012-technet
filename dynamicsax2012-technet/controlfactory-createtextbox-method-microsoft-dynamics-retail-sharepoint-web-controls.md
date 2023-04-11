---
title: ControlFactory.CreateTextBox Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Controls)
TOCTitle: CreateTextBox Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Controls.ControlFactory.CreateTextBox(System.String,System.Int32)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.controls.controlfactory.createtextbox(v=AX.60)
ms:contentKeyID: 62202363
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Controls.ControlFactory.CreateTextBox
dev_langs:
- CSharp
- C++
- VB
---

# CreateTextBox Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Create a .NET TextBox control.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Controls](microsoft-dynamics-retail-sharepoint-web-controls-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Controls (in Microsoft.Dynamics.Retail.SP.Web.Controls.dll)

## Syntax

``` vb
'Declaration
Public Shared Function CreateTextBox ( _
    className As String, _
    maxLength As Integer _
) As HtmlInputText
'Usage
Dim className As String
Dim maxLength As Integer
Dim returnValue As HtmlInputText

returnValue = ControlFactory.CreateTextBox(className, _
    maxLength)
```

``` csharp
public static HtmlInputText CreateTextBox(
    string className,
    int maxLength
)
```

``` c++
public:
static HtmlInputText^ CreateTextBox(
    String^ className, 
    int maxLength
)
```

#### Parameters

  - className  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - maxLength  
    Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

#### Return Value

Type: [System.Web.UI.HtmlControls.HtmlInputText](https://technet.microsoft.com/library/hx8x1zw4\(v=ax.60\))  
A TextBox instance.  

## See Also

#### Reference

[ControlFactory Class](controlfactory-class-microsoft-dynamics-retail-sharepoint-web-controls.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Controls Namespace](microsoft-dynamics-retail-sharepoint-web-controls-namespace.md)

