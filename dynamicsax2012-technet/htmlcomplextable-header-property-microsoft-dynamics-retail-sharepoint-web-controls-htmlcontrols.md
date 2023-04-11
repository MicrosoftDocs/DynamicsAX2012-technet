---
title: HtmlComplexTable.Header Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Controls.HtmlControls)
TOCTitle: Header Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Controls.HtmlControls.HtmlComplexTable.Header
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.controls.htmlcontrols.htmlcomplextable.header(v=AX.60)
ms:contentKeyID: 62206318
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Controls.HtmlControls.HtmlComplexTable.Header
dev_langs:
- CSharp
- C++
- VB
---

# Header Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the header rows.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Controls.HtmlControls](microsoft-dynamics-retail-sharepoint-web-controls-htmlcontrols-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Controls (in Microsoft.Dynamics.Retail.SP.Web.Controls.dll)

## Syntax

``` vb
'Declaration
Public Property Header As Collection(Of HtmlTableRow)
    Get
    Set
'Usage
Dim instance As HtmlComplexTable
Dim value As Collection(Of HtmlTableRow)

value = instance.Header

instance.Header = value
```

``` csharp
public Collection<HtmlTableRow> Header { get; set; }
```

``` c++
public:
property Collection<HtmlTableRow^>^ Header {
    Collection<HtmlTableRow^>^ get ();
    void set (Collection<HtmlTableRow^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/library/ms132397\(v=ax.60\))\<[HtmlTableRow](https://technet.microsoft.com/library/3x5s86zd\(v=ax.60\))\>  
Returns [Collection\<T\>](https://technet.microsoft.com/library/ms132397\(v=ax.60\)).  

## See Also

#### Reference

[HtmlComplexTable Class](htmlcomplextable-class-microsoft-dynamics-retail-sharepoint-web-controls-htmlcontrols.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Controls.HtmlControls Namespace](microsoft-dynamics-retail-sharepoint-web-controls-htmlcontrols-namespace.md)

