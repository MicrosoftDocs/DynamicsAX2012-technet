---
title: HtmlControlExtensions.AddCssClass Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Controls.HtmlControls)
TOCTitle: AddCssClass Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Controls.HtmlControls.HtmlControlExtensions.AddCssClass(System.Web.UI.HtmlControls.HtmlControl,System.String[])
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.web.controls.htmlcontrols.htmlcontrolextensions.addcssclass(v=AX.60)
ms:contentKeyID: 62206105
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Controls.HtmlControls.HtmlControlExtensions.AddCssClass
dev_langs:
- CSharp
- C++
- VB
---

# AddCssClass Method

Adds a CSS class to the 'class' attribute.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Controls.HtmlControls](microsoft-dynamics-retail-sharepoint-web-controls-htmlcontrols-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Controls (in Microsoft.Dynamics.Retail.SP.Web.Controls.dll)

## Syntax

``` vb
'Declaration
<ExtensionAttribute> _
Public Shared Sub AddCssClass ( _
    control As HtmlControl, _
    ParamArray cssClasses As String() _
)
'Usage
Dim control As HtmlControl
Dim cssClasses As String()

control.AddCssClass(cssClasses)
```

``` csharp
public static void AddCssClass(
    this HtmlControl control,
    params string[] cssClasses
)
```

``` c++
[ExtensionAttribute]
public:
static void AddCssClass(
    HtmlControl^ control, 
    ... array<String^>^ cssClasses
)
```

#### Parameters

  - control  
    Type: [System.Web.UI.HtmlControls.HtmlControl](https://technet.microsoft.com/en-us/library/khc6t495\(v=ax.60\))  

<!-- end list -->

  - cssClasses  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))\[\]  

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [HtmlControl](https://technet.microsoft.com/en-us/library/khc6t495\(v=ax.60\)). When you use instance method syntax to call this method, omit the first parameter. For more information, see b8020aae-374d-46a9-bcb7-8cc2390b93b6 or 175ce3ff-9bbf-4e64-8421-faeb81a0bb51.

## See Also

#### Reference

[HtmlControlExtensions Class](htmlcontrolextensions-class-microsoft-dynamics-retail-sharepoint-web-controls-htmlcontrols.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Controls.HtmlControls Namespace](microsoft-dynamics-retail-sharepoint-web-controls-htmlcontrols-namespace.md)

