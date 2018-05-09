---
title: ControlFactory.CreateRadioButtons Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Controls)
TOCTitle: CreateRadioButtons Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Controls.ControlFactory.CreateRadioButtons(System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.web.controls.controlfactory.createradiobuttons(v=AX.60)
ms:contentKeyID: 62202453
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Controls.ControlFactory.CreateRadioButtons
dev_langs:
- CSharp
- C++
- VB
---

# CreateRadioButtons Method

Create a .NET radio button control.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Controls](microsoft-dynamics-retail-sharepoint-web-controls-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Controls (in Microsoft.Dynamics.Retail.SP.Web.Controls.dll)

## Syntax

``` vb
'Declaration
Public Shared Function CreateRadioButtons ( _
    groupName As String, _
    className As String _
) As HtmlRadioButtons
'Usage
Dim groupName As String
Dim className As String
Dim returnValue As HtmlRadioButtons

returnValue = ControlFactory.CreateRadioButtons(groupName, _
    className)
```

``` csharp
public static HtmlRadioButtons CreateRadioButtons(
    string groupName,
    string className
)
```

``` c++
public:
static HtmlRadioButtons^ CreateRadioButtons(
    String^ groupName, 
    String^ className
)
```

#### Parameters

  - groupName  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - className  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Controls.HtmlControls.HtmlRadioButtons](htmlradiobuttons-class-microsoft-dynamics-retail-sharepoint-web-controls-htmlcontrols.md)  
A DropDownList instance.  

## See Also

#### Reference

[ControlFactory Class](controlfactory-class-microsoft-dynamics-retail-sharepoint-web-controls.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Controls Namespace](microsoft-dynamics-retail-sharepoint-web-controls-namespace.md)

