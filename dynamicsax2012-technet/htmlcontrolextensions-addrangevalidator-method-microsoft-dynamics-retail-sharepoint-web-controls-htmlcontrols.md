---
title: HtmlControlExtensions.AddRangeValidator Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Controls.HtmlControls)
TOCTitle: AddRangeValidator Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Controls.HtmlControls.HtmlControlExtensions.AddRangeValidator(System.Web.UI.HtmlControls.HtmlControl,System.String,System.String,System.String,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.controls.htmlcontrols.htmlcontrolextensions.addrangevalidator(v=AX.60)
ms:contentKeyID: 62206662
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Controls.HtmlControls.HtmlControlExtensions.AddRangeValidator
dev_langs:
- CSharp
- C++
- VB
---

# AddRangeValidator Method

Adds the Range Validator to the input element.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Controls.HtmlControls](microsoft-dynamics-retail-sharepoint-web-controls-htmlcontrols-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Controls (in Microsoft.Dynamics.Retail.SP.Web.Controls.dll)

## Syntax

``` vb
'Declaration
<ExtensionAttribute> _
Public Shared Sub AddRangeValidator ( _
    control As HtmlControl, _
    message As String, _
    minimumValue As String, _
    maximumValue As String, _
    isNumeric As Boolean _
)
'Usage
Dim control As HtmlControl
Dim message As String
Dim minimumValue As String
Dim maximumValue As String
Dim isNumeric As Boolean

control.AddRangeValidator(message, _
    minimumValue, maximumValue, isNumeric)
```

``` csharp
public static void AddRangeValidator(
    this HtmlControl control,
    string message,
    string minimumValue,
    string maximumValue,
    bool isNumeric
)
```

``` c++
[ExtensionAttribute]
public:
static void AddRangeValidator(
    HtmlControl^ control, 
    String^ message, 
    String^ minimumValue, 
    String^ maximumValue, 
    bool isNumeric
)
```

#### Parameters

  - control  
    Type: [System.Web.UI.HtmlControls.HtmlControl](https://technet.microsoft.com/library/khc6t495\(v=ax.60\))  

<!-- end list -->

  - message  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - minimumValue  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - maximumValue  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - isNumeric  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [HtmlControl](https://technet.microsoft.com/library/khc6t495\(v=ax.60\)). When you use instance method syntax to call this method, omit the first parameter. For more information, see b8020aae-374d-46a9-bcb7-8cc2390b93b6 or 175ce3ff-9bbf-4e64-8421-faeb81a0bb51.

## See Also

#### Reference

[HtmlControlExtensions Class](htmlcontrolextensions-class-microsoft-dynamics-retail-sharepoint-web-controls-htmlcontrols.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Controls.HtmlControls Namespace](microsoft-dynamics-retail-sharepoint-web-controls-htmlcontrols-namespace.md)

