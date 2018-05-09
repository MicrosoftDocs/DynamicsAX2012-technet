---
title: ControlFactory.CreateTableRow Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Controls)
TOCTitle: CreateTableRow Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Controls.ControlFactory.CreateTableRow(System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.web.controls.controlfactory.createtablerow(v=AX.60)
ms:contentKeyID: 62205901
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Controls.ControlFactory.CreateTableRow
dev_langs:
- CSharp
- C++
- VB
---

# CreateTableRow Method

Create table row.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Controls](microsoft-dynamics-retail-sharepoint-web-controls-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Controls (in Microsoft.Dynamics.Retail.SP.Web.Controls.dll)

## Syntax

``` vb
'Declaration
Public Shared Function CreateTableRow ( _
    className As String, _
    forEachBindingField As String _
) As HtmlTableRow
'Usage
Dim className As String
Dim forEachBindingField As String
Dim returnValue As HtmlTableRow

returnValue = ControlFactory.CreateTableRow(className, _
    forEachBindingField)
```

``` csharp
public static HtmlTableRow CreateTableRow(
    string className,
    string forEachBindingField
)
```

``` c++
public:
static HtmlTableRow^ CreateTableRow(
    String^ className, 
    String^ forEachBindingField
)
```

#### Parameters

  - className  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - forEachBindingField  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Web.UI.HtmlControls.HtmlTableRow](https://technet.microsoft.com/en-us/library/3x5s86zd\(v=ax.60\))  
The table row instance.  

## See Also

#### Reference

[ControlFactory Class](controlfactory-class-microsoft-dynamics-retail-sharepoint-web-controls.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Controls Namespace](microsoft-dynamics-retail-sharepoint-web-controls-namespace.md)

