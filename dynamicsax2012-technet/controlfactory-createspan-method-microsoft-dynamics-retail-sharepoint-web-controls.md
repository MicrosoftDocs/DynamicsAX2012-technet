---
title: ControlFactory.CreateSpan Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Controls)
TOCTitle: CreateSpan Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Controls.ControlFactory.CreateSpan(System.String,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.controls.controlfactory.createspan(v=AX.60)
ms:contentKeyID: 62204701
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Controls.ControlFactory.CreateSpan
dev_langs:
- CSharp
- C++
- VB
---

# CreateSpan Method

Creates a inline text element (span) for inserting text.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Controls](microsoft-dynamics-retail-sharepoint-web-controls-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Controls (in Microsoft.Dynamics.Retail.SP.Web.Controls.dll)

## Syntax

``` vb
'Declaration
Public Shared Function CreateSpan ( _
    text As String, _
    className As String, _
    bindingField As String _
) As HtmlSpan
'Usage
Dim text As String
Dim className As String
Dim bindingField As String
Dim returnValue As HtmlSpan

returnValue = ControlFactory.CreateSpan(text, _
    className, bindingField)
```

``` csharp
public static HtmlSpan CreateSpan(
    string text,
    string className,
    string bindingField
)
```

``` c++
public:
static HtmlSpan^ CreateSpan(
    String^ text, 
    String^ className, 
    String^ bindingField
)
```

#### Parameters

  - text  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - className  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - bindingField  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Controls.HtmlControls.HtmlSpan](htmlspan-class-microsoft-dynamics-retail-sharepoint-web-controls-htmlcontrols.md)  
A HtmlSpan element containing the text to display.  

## See Also

#### Reference

[ControlFactory Class](controlfactory-class-microsoft-dynamics-retail-sharepoint-web-controls.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Controls Namespace](microsoft-dynamics-retail-sharepoint-web-controls-namespace.md)

