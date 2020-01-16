---
title: ControlFactory.CreateImage Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Controls)
TOCTitle: CreateImage Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Controls.ControlFactory.CreateImage(System.String,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.controls.controlfactory.createimage(v=AX.60)
ms:contentKeyID: 62207355
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Controls.ControlFactory.CreateImage
dev_langs:
- CSharp
- C++
- VB
---

# CreateImage Method

Create a .NET HTML Image control.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Controls](microsoft-dynamics-retail-sharepoint-web-controls-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Controls (in Microsoft.Dynamics.Retail.SP.Web.Controls.dll)

## Syntax

``` vb
'Declaration
Public Shared Function CreateImage ( _
    imageUrl As String, _
    altText As String, _
    className As String _
) As HtmlImage
'Usage
Dim imageUrl As String
Dim altText As String
Dim className As String
Dim returnValue As HtmlImage

returnValue = ControlFactory.CreateImage(imageUrl, _
    altText, className)
```

``` csharp
public static HtmlImage CreateImage(
    string imageUrl,
    string altText,
    string className
)
```

``` c++
public:
static HtmlImage^ CreateImage(
    String^ imageUrl, 
    String^ altText, 
    String^ className
)
```

#### Parameters

  - imageUrl  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - altText  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - className  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Web.UI.HtmlControls.HtmlImage](https://technet.microsoft.com/library/kd9cwet3\(v=ax.60\))  
An HtmlImage instance.  

## See Also

#### Reference

[ControlFactory Class](controlfactory-class-microsoft-dynamics-retail-sharepoint-web-controls.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Controls Namespace](microsoft-dynamics-retail-sharepoint-web-controls-namespace.md)

