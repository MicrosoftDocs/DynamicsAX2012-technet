---
title: HtmlRadioButtons.AddRadioButton Method (String, String, Boolean, HtmlControl) (Microsoft.Dynamics.Retail.SharePoint.Web.Controls.HtmlControls)
TOCTitle: AddRadioButton Method (String, String, Boolean, HtmlControl)
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Controls.HtmlControls.HtmlRadioButtons.AddRadioButton(System.String,System.String,System.Boolean,System.Web.UI.HtmlControls.HtmlControl)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.web.controls.htmlcontrols.htmlradiobuttons.addradiobutton(v=AX.60)
ms:contentKeyID: 62207667
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# AddRadioButton Method (String, String, Boolean, HtmlControl)

Adds a radio button to the group with the specified text, value and checked.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Controls.HtmlControls](microsoft-dynamics-retail-sharepoint-web-controls-htmlcontrols-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Controls (in Microsoft.Dynamics.Retail.SP.Web.Controls.dll)

## Syntax

``` vb
'Declaration
Public Sub AddRadioButton ( _
    text As String, _
    value As String, _
    isChecked As Boolean, _
    container As HtmlControl _
)
'Usage
Dim instance As HtmlRadioButtons
Dim text As String
Dim value As String
Dim isChecked As Boolean
Dim container As HtmlControl

instance.AddRadioButton(text, value, isChecked, _
    container)
```

``` csharp
public void AddRadioButton(
    string text,
    string value,
    bool isChecked,
    HtmlControl container
)
```

``` c++
public:
void AddRadioButton(
    String^ text, 
    String^ value, 
    bool isChecked, 
    HtmlControl^ container
)
```

#### Parameters

  - text  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - value  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - isChecked  
    Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - container  
    Type: [System.Web.UI.HtmlControls.HtmlControl](https://technet.microsoft.com/en-us/library/khc6t495\(v=ax.60\))  

## See Also

#### Reference

[HtmlRadioButtons Class](htmlradiobuttons-class-microsoft-dynamics-retail-sharepoint-web-controls-htmlcontrols.md)

[AddRadioButton Overload](htmlradiobuttons-addradiobutton-method-microsoft-dynamics-retail-sharepoint-web-controls-htmlcontrols.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Controls.HtmlControls Namespace](microsoft-dynamics-retail-sharepoint-web-controls-htmlcontrols-namespace.md)

