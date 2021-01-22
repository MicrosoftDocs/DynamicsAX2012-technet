---
title: ControlFactory.CreateImageButton Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Controls)
TOCTitle: CreateImageButton Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Controls.ControlFactory.CreateImageButton(System.String,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.controls.controlfactory.createimagebutton(v=AX.60)
ms:contentKeyID: 62207311
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Controls.ControlFactory.CreateImageButton
dev_langs:
- CSharp
- C++
- VB
---

# CreateImageButton Method

Create a .NET HTML Image Button control.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Controls](microsoft-dynamics-retail-sharepoint-web-controls-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Controls (in Microsoft.Dynamics.Retail.SP.Web.Controls.dll)

## Syntax

``` vb
'Declaration
Public Shared Function CreateImageButton ( _
    imageUrl As String, _
    altText As String, _
    className As String _
) As HtmlInputImage
'Usage
Dim imageUrl As String
Dim altText As String
Dim className As String
Dim returnValue As HtmlInputImage

returnValue = ControlFactory.CreateImageButton(imageUrl, _
    altText, className)
```

``` csharp
public static HtmlInputImage CreateImageButton(
    string imageUrl,
    string altText,
    string className
)
```

``` c++
public:
static HtmlInputImage^ CreateImageButton(
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

Type: [System.Web.UI.HtmlControls.HtmlInputImage](https://technet.microsoft.com/library/5x5ezdx1\(v=ax.60\))  
An HtmlButton instance.  

## See Also

#### Reference

[ControlFactory Class](controlfactory-class-microsoft-dynamics-retail-sharepoint-web-controls.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Controls Namespace](microsoft-dynamics-retail-sharepoint-web-controls-namespace.md)

