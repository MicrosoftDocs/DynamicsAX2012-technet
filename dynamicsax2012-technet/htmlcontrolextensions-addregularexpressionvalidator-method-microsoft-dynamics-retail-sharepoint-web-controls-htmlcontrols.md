---
title: HtmlControlExtensions.AddRegularExpressionValidator Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Controls.HtmlControls)
TOCTitle: AddRegularExpressionValidator Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Controls.HtmlControls.HtmlControlExtensions.AddRegularExpressionValidator(System.Web.UI.HtmlControls.HtmlControl,System.String,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.web.controls.htmlcontrols.htmlcontrolextensions.addregularexpressionvalidator(v=AX.60)
ms:contentKeyID: 62202314
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Controls.HtmlControls.HtmlControlExtensions.AddRegularExpressionValidator
dev_langs:
- CSharp
- C++
- VB
---

# AddRegularExpressionValidator Method

Adds the Regular Expression Validator to the input element.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Controls.HtmlControls](microsoft-dynamics-retail-sharepoint-web-controls-htmlcontrols-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Controls (in Microsoft.Dynamics.Retail.SP.Web.Controls.dll)

## Syntax

``` vb
'Declaration
<ExtensionAttribute> _
Public Shared Sub AddRegularExpressionValidator ( _
    control As HtmlControl, _
    message As String, _
    regularExpression As String, _
    modifiers As String _
)
'Usage
Dim control As HtmlControl
Dim message As String
Dim regularExpression As String
Dim modifiers As String

control.AddRegularExpressionValidator(message, _
    regularExpression, modifiers)
```

``` csharp
public static void AddRegularExpressionValidator(
    this HtmlControl control,
    string message,
    string regularExpression,
    string modifiers
)
```

``` c++
[ExtensionAttribute]
public:
static void AddRegularExpressionValidator(
    HtmlControl^ control, 
    String^ message, 
    String^ regularExpression, 
    String^ modifiers
)
```

#### Parameters

  - control  
    Type: [System.Web.UI.HtmlControls.HtmlControl](https://technet.microsoft.com/en-us/library/khc6t495\(v=ax.60\))  

<!-- end list -->

  - message  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - regularExpression  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - modifiers  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [HtmlControl](https://technet.microsoft.com/en-us/library/khc6t495\(v=ax.60\)). When you use instance method syntax to call this method, omit the first parameter. For more information, see b8020aae-374d-46a9-bcb7-8cc2390b93b6 or 175ce3ff-9bbf-4e64-8421-faeb81a0bb51.

## See Also

#### Reference

[HtmlControlExtensions Class](htmlcontrolextensions-class-microsoft-dynamics-retail-sharepoint-web-controls-htmlcontrols.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Controls.HtmlControls Namespace](microsoft-dynamics-retail-sharepoint-web-controls-htmlcontrols-namespace.md)

