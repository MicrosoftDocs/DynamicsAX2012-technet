---
title: ControlFactory.CreateTableHeaderCell Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Controls)
TOCTitle: CreateTableHeaderCell Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Controls.ControlFactory.CreateTableHeaderCell(System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.controls.controlfactory.createtableheadercell(v=AX.60)
ms:contentKeyID: 62206468
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Controls.ControlFactory.CreateTableHeaderCell
dev_langs:
- CSharp
- C++
- VB
---

# CreateTableHeaderCell Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Create header cell.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Controls](microsoft-dynamics-retail-sharepoint-web-controls-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Controls (in Microsoft.Dynamics.Retail.SP.Web.Controls.dll)

## Syntax

``` vb
'Declaration
Public Shared Function CreateTableHeaderCell ( _
    className As String, _
    text As String _
) As HtmlTableCell
'Usage
Dim className As String
Dim text As String
Dim returnValue As HtmlTableCell

returnValue = ControlFactory.CreateTableHeaderCell(className, _
    text)
```

``` csharp
public static HtmlTableCell CreateTableHeaderCell(
    string className,
    string text
)
```

``` c++
public:
static HtmlTableCell^ CreateTableHeaderCell(
    String^ className, 
    String^ text
)
```

#### Parameters

  - className  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - text  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Web.UI.HtmlControls.HtmlTableCell](https://technet.microsoft.com/library/c4x7t5s1\(v=ax.60\))  
The header cell instance.  

## See Also

#### Reference

[ControlFactory Class](controlfactory-class-microsoft-dynamics-retail-sharepoint-web-controls.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Controls Namespace](microsoft-dynamics-retail-sharepoint-web-controls-namespace.md)

