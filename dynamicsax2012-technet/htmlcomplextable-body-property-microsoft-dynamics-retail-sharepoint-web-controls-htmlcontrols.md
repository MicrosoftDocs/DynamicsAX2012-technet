---
title: HtmlComplexTable.Body Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Controls.HtmlControls)
TOCTitle: Body Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Controls.HtmlControls.HtmlComplexTable.Body
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.web.controls.htmlcontrols.htmlcomplextable.body(v=AX.60)
ms:contentKeyID: 62206418
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Controls.HtmlControls.HtmlComplexTable.Body
dev_langs:
- CSharp
- C++
- VB
---

# Body Property

Gets or sets the body rows.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Controls.HtmlControls](microsoft-dynamics-retail-sharepoint-web-controls-htmlcontrols-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Controls (in Microsoft.Dynamics.Retail.SP.Web.Controls.dll)

## Syntax

``` vb
'Declaration
Public Property Body As Collection(Of HtmlTableRow)
    Get
    Set
'Usage
Dim instance As HtmlComplexTable
Dim value As Collection(Of HtmlTableRow)

value = instance.Body

instance.Body = value
```

``` csharp
public Collection<HtmlTableRow> Body { get; set; }
```

``` c++
public:
property Collection<HtmlTableRow^>^ Body {
    Collection<HtmlTableRow^>^ get ();
    void set (Collection<HtmlTableRow^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/en-us/library/ms132397\(v=ax.60\))\<[HtmlTableRow](https://technet.microsoft.com/en-us/library/3x5s86zd\(v=ax.60\))\>  
Returns [Collection\<T\>](https://technet.microsoft.com/en-us/library/ms132397\(v=ax.60\)).  

## See Also

#### Reference

[HtmlComplexTable Class](htmlcomplextable-class-microsoft-dynamics-retail-sharepoint-web-controls-htmlcontrols.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Controls.HtmlControls Namespace](microsoft-dynamics-retail-sharepoint-web-controls-htmlcontrols-namespace.md)

