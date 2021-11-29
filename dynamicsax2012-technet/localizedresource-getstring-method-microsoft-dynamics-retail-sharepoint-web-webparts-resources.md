---
title: LocalizedResource.GetString Method  (Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.Resources)
TOCTitle: GetString Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.Resources.LocalizedResource.GetString(System.String,System.Globalization.CultureInfo)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.webparts.resources.localizedresource.getstring(v=AX.60)
ms:contentKeyID: 62207375
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.Resources.LocalizedResource.GetString
dev_langs:
- CSharp
- C++
- VB
---

# GetString Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a localized string.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.Resources](microsoft-dynamics-retail-sharepoint-web-webparts-resources-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.WebParts (in Microsoft.Dynamics.Retail.SP.Web.WebParts.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GetString ( _
    resourceName As String, _
    cultureInfo As CultureInfo _
) As String
'Usage
Dim resourceName As String
Dim cultureInfo As CultureInfo
Dim returnValue As String

returnValue = LocalizedResource.GetString(resourceName, _
    cultureInfo)
```

``` csharp
public static string GetString(
    string resourceName,
    CultureInfo cultureInfo
)
```

``` c++
public:
static String^ GetString(
    String^ resourceName, 
    CultureInfo^ cultureInfo
)
```

#### Parameters

  - resourceName  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - cultureInfo  
    Type: [System.Globalization.CultureInfo](https://technet.microsoft.com/library/kx54z3k7\(v=ax.60\))  

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
A localized string.  

## See Also

#### Reference

[LocalizedResource Class](localizedresource-class-microsoft-dynamics-retail-sharepoint-web-webparts-resources.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.Resources Namespace](microsoft-dynamics-retail-sharepoint-web-webparts-resources-namespace.md)

