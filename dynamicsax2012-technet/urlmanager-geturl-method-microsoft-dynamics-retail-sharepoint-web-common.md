---
title: UrlManager.GetUrl Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Common)
TOCTitle: GetUrl Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Common.UrlManager.GetUrl(System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.common.urlmanager.geturl(v=AX.60)
ms:contentKeyID: 62202695
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Common.UrlManager.GetUrl
dev_langs:
- CSharp
- C++
- VB
---

# GetUrl Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a url for the page and return url values.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Common](microsoft-dynamics-retail-sharepoint-web-common-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GetUrl ( _
    pageName As String, _
    returnUrl As String _
) As String
'Usage
Dim pageName As String
Dim returnUrl As String
Dim returnValue As String

returnValue = UrlManager.GetUrl(pageName, _
    returnUrl)
```

``` csharp
public static string GetUrl(
    string pageName,
    string returnUrl
)
```

``` c++
public:
static String^ GetUrl(
    String^ pageName, 
    String^ returnUrl
)
```

#### Parameters

  - pageName  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - returnUrl  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The relative URL.  

## See Also

#### Reference

[UrlManager Class](urlmanager-class-microsoft-dynamics-retail-sharepoint-web-common.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Common Namespace](microsoft-dynamics-retail-sharepoint-web-common-namespace.md)

