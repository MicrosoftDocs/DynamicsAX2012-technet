---
title: ControlFactory.CreateDropDown Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Controls)
TOCTitle: CreateDropDown Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Controls.ControlFactory.CreateDropDown(System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.web.controls.controlfactory.createdropdown(v=AX.60)
ms:contentKeyID: 62205455
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Controls.ControlFactory.CreateDropDown
dev_langs:
- CSharp
- C++
- VB
---

# CreateDropDown Method

Create a .NET DropDown control.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Controls](microsoft-dynamics-retail-sharepoint-web-controls-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Controls (in Microsoft.Dynamics.Retail.SP.Web.Controls.dll)

## Syntax

``` vb
'Declaration
Public Shared Function CreateDropDown ( _
    className As String _
) As HtmlSelect
'Usage
Dim className As String
Dim returnValue As HtmlSelect

returnValue = ControlFactory.CreateDropDown(className)
```

``` csharp
public static HtmlSelect CreateDropDown(
    string className
)
```

``` c++
public:
static HtmlSelect^ CreateDropDown(
    String^ className
)
```

#### Parameters

  - className  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Web.UI.HtmlControls.HtmlSelect](https://technet.microsoft.com/en-us/library/xf11z4ad\(v=ax.60\))  
A drop downList instance.  

## See Also

#### Reference

[ControlFactory Class](controlfactory-class-microsoft-dynamics-retail-sharepoint-web-controls.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Controls Namespace](microsoft-dynamics-retail-sharepoint-web-controls-namespace.md)

