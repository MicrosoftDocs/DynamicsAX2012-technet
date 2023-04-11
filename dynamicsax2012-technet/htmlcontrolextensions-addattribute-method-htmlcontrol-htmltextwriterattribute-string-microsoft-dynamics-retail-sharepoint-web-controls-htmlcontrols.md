---
title: HtmlControlExtensions.AddAttribute Method (HtmlControl, HtmlTextWriterAttribute, String) (Microsoft.Dynamics.Retail.SharePoint.Web.Controls.HtmlControls)
TOCTitle: AddAttribute Method (HtmlControl, HtmlTextWriterAttribute, String)
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Controls.HtmlControls.HtmlControlExtensions.AddAttribute(System.Web.UI.HtmlControls.HtmlControl,System.Web.UI.HtmlTextWriterAttribute,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.controls.htmlcontrols.htmlcontrolextensions.addattribute(v=AX.60)
ms:contentKeyID: 62207672
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# AddAttribute Method (HtmlControl, HtmlTextWriterAttribute, String)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Adds the specified attribute to the element.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Controls.HtmlControls](microsoft-dynamics-retail-sharepoint-web-controls-htmlcontrols-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Controls (in Microsoft.Dynamics.Retail.SP.Web.Controls.dll)

## Syntax

``` vb
'Declaration
<ExtensionAttribute> _
Public Shared Sub AddAttribute ( _
    control As HtmlControl, _
    attribute As HtmlTextWriterAttribute, _
    attributeValue As String _
)
'Usage
Dim control As HtmlControl
Dim attribute As HtmlTextWriterAttribute
Dim attributeValue As String

control.AddAttribute(attribute, attributeValue)
```

``` csharp
public static void AddAttribute(
    this HtmlControl control,
    HtmlTextWriterAttribute attribute,
    string attributeValue
)
```

``` c++
[ExtensionAttribute]
public:
static void AddAttribute(
    HtmlControl^ control, 
    HtmlTextWriterAttribute attribute, 
    String^ attributeValue
)
```

#### Parameters

  - control  
    Type: [System.Web.UI.HtmlControls.HtmlControl](https://technet.microsoft.com/library/khc6t495\(v=ax.60\))  

<!-- end list -->

  - attribute  
    Type: [System.Web.UI.HtmlTextWriterAttribute](https://technet.microsoft.com/library/31x5505f\(v=ax.60\))  

<!-- end list -->

  - attributeValue  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [HtmlControl](https://technet.microsoft.com/library/khc6t495\(v=ax.60\)). When you use instance method syntax to call this method, omit the first parameter. For more information, see b8020aae-374d-46a9-bcb7-8cc2390b93b6 or 175ce3ff-9bbf-4e64-8421-faeb81a0bb51.

## See Also

#### Reference

[HtmlControlExtensions Class](htmlcontrolextensions-class-microsoft-dynamics-retail-sharepoint-web-controls-htmlcontrols.md)

[AddAttribute Overload](htmlcontrolextensions-addattribute-method-microsoft-dynamics-retail-sharepoint-web-controls-htmlcontrols.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Controls.HtmlControls Namespace](microsoft-dynamics-retail-sharepoint-web-controls-htmlcontrols-namespace.md)

