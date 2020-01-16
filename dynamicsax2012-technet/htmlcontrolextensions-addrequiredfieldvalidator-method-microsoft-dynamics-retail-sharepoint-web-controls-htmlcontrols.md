---
title: HtmlControlExtensions.AddRequiredFieldValidator Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Controls.HtmlControls)
TOCTitle: AddRequiredFieldValidator Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Controls.HtmlControls.HtmlControlExtensions.AddRequiredFieldValidator(System.Web.UI.HtmlControls.HtmlControl,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.controls.htmlcontrols.htmlcontrolextensions.addrequiredfieldvalidator(v=AX.60)
ms:contentKeyID: 62207333
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Controls.HtmlControls.HtmlControlExtensions.AddRequiredFieldValidator
dev_langs:
- CSharp
- C++
- VB
---

# AddRequiredFieldValidator Method

Adds the Required Field Validator to the input element.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Controls.HtmlControls](microsoft-dynamics-retail-sharepoint-web-controls-htmlcontrols-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Controls (in Microsoft.Dynamics.Retail.SP.Web.Controls.dll)

## Syntax

``` vb
'Declaration
<ExtensionAttribute> _
Public Shared Sub AddRequiredFieldValidator ( _
    control As HtmlControl, _
    message As String, _
    defaultValue As String _
)
'Usage
Dim control As HtmlControl
Dim message As String
Dim defaultValue As String

control.AddRequiredFieldValidator(message, _
    defaultValue)
```

``` csharp
public static void AddRequiredFieldValidator(
    this HtmlControl control,
    string message,
    string defaultValue
)
```

``` c++
[ExtensionAttribute]
public:
static void AddRequiredFieldValidator(
    HtmlControl^ control, 
    String^ message, 
    String^ defaultValue
)
```

#### Parameters

  - control  
    Type: [System.Web.UI.HtmlControls.HtmlControl](https://technet.microsoft.com/library/khc6t495\(v=ax.60\))  

<!-- end list -->

  - message  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - defaultValue  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [HtmlControl](https://technet.microsoft.com/library/khc6t495\(v=ax.60\)). When you use instance method syntax to call this method, omit the first parameter. For more information, see b8020aae-374d-46a9-bcb7-8cc2390b93b6 or 175ce3ff-9bbf-4e64-8421-faeb81a0bb51.

## See Also

#### Reference

[HtmlControlExtensions Class](htmlcontrolextensions-class-microsoft-dynamics-retail-sharepoint-web-controls-htmlcontrols.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Controls.HtmlControls Namespace](microsoft-dynamics-retail-sharepoint-web-controls-htmlcontrols-namespace.md)

