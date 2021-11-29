---
title: ControlFactory.CreateTableCell Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Controls)
TOCTitle: CreateTableCell Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Controls.ControlFactory.CreateTableCell(System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.controls.controlfactory.createtablecell(v=AX.60)
ms:contentKeyID: 62204250
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Controls.ControlFactory.CreateTableCell
dev_langs:
- CSharp
- C++
- VB
---

# CreateTableCell Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Create table cell.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Controls](microsoft-dynamics-retail-sharepoint-web-controls-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Controls (in Microsoft.Dynamics.Retail.SP.Web.Controls.dll)

## Syntax

``` vb
'Declaration
Public Shared Function CreateTableCell ( _
    className As String, _
    bindingField As String _
) As HtmlTableCell
'Usage
Dim className As String
Dim bindingField As String
Dim returnValue As HtmlTableCell

returnValue = ControlFactory.CreateTableCell(className, _
    bindingField)
```

``` csharp
public static HtmlTableCell CreateTableCell(
    string className,
    string bindingField
)
```

``` c++
public:
static HtmlTableCell^ CreateTableCell(
    String^ className, 
    String^ bindingField
)
```

#### Parameters

  - className  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - bindingField  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Web.UI.HtmlControls.HtmlTableCell](https://technet.microsoft.com/library/c4x7t5s1\(v=ax.60\))  
The table cell instance.  

## See Also

#### Reference

[ControlFactory Class](controlfactory-class-microsoft-dynamics-retail-sharepoint-web-controls.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Controls Namespace](microsoft-dynamics-retail-sharepoint-web-controls-namespace.md)

