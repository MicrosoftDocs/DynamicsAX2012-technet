---
title: LocalizedWebDisplayNameAttribute.DisplayName Property  (Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.Resources)
TOCTitle: DisplayName Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.Resources.LocalizedWebDisplayNameAttribute.DisplayName
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.web.webparts.resources.localizedwebdisplaynameattribute.displayname(v=AX.60)
ms:contentKeyID: 62203328
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.Resources.LocalizedWebDisplayNameAttribute.DisplayName
dev_langs:
- CSharp
- C++
- VB
---

# DisplayName Property

Return value from the webpart's resource file.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.Resources](microsoft-dynamics-retail-sharepoint-web-webparts-resources-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.WebParts (in Microsoft.Dynamics.Retail.SP.Web.WebParts.dll)

## Syntax

``` vb
'Declaration
Public Overrides ReadOnly Property DisplayName As String
    Get
'Usage
Dim instance As LocalizedWebDisplayNameAttribute
Dim value As String

value = instance.DisplayName
```

``` csharp
public override string DisplayName { get; }
```

``` c++
public:
virtual property String^ DisplayName {
    String^ get () override;
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
A localized string.  

## See Also

#### Reference

[LocalizedWebDisplayNameAttribute Class](localizedwebdisplaynameattribute-class-microsoft-dynamics-retail-sharepoint-web-webparts-resources.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.Resources Namespace](microsoft-dynamics-retail-sharepoint-web-webparts-resources-namespace.md)

