---
title: LocalizedWebDescriptionAttribute.Description Property  (Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.Resources)
TOCTitle: Description Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.Resources.LocalizedWebDescriptionAttribute.Description
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.webparts.resources.localizedwebdescriptionattribute.description(v=AX.60)
ms:contentKeyID: 62204058
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.Resources.LocalizedWebDescriptionAttribute.Description
dev_langs:
- CSharp
- C++
- VB
---

# Description Property

Return value from the webpart's resource file.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.Resources](microsoft-dynamics-retail-sharepoint-web-webparts-resources-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.WebParts (in Microsoft.Dynamics.Retail.SP.Web.WebParts.dll)

## Syntax

``` vb
'Declaration
Public Overrides ReadOnly Property Description As String
    Get
'Usage
Dim instance As LocalizedWebDescriptionAttribute
Dim value As String

value = instance.Description
```

``` csharp
public override string Description { get; }
```

``` c++
public:
virtual property String^ Description {
    String^ get () override;
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
A localized string.  

## See Also

#### Reference

[LocalizedWebDescriptionAttribute Class](localizedwebdescriptionattribute-class-microsoft-dynamics-retail-sharepoint-web-webparts-resources.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.Resources Namespace](microsoft-dynamics-retail-sharepoint-web-webparts-resources-namespace.md)

