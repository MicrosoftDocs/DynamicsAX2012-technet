---
title: UrlManager.VerifyUrlInSiteDomain Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Common)
TOCTitle: VerifyUrlInSiteDomain Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Common.UrlManager.VerifyUrlInSiteDomain(System.Uri)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.common.urlmanager.verifyurlinsitedomain(v=AX.60)
ms:contentKeyID: 62206677
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Common.UrlManager.VerifyUrlInSiteDomain
dev_langs:
- CSharp
- C++
- VB
---

# VerifyUrlInSiteDomain Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Function to verify that a given url is the same domain as the current site

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Common](microsoft-dynamics-retail-sharepoint-web-common-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Shared Function VerifyUrlInSiteDomain ( _
    url As Uri _
) As Boolean
'Usage
Dim url As Uri
Dim returnValue As Boolean

returnValue = UrlManager.VerifyUrlInSiteDomain(url)
```

``` csharp
public static bool VerifyUrlInSiteDomain(
    Uri url
)
```

``` c++
public:
static bool VerifyUrlInSiteDomain(
    Uri^ url
)
```

#### Parameters

  - url  
    Type: [System.Uri](https://technet.microsoft.com/library/txt7706a\(v=ax.60\))  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
true if the url is the same domain, false otherwise  

## See Also

#### Reference

[UrlManager Class](urlmanager-class-microsoft-dynamics-retail-sharepoint-web-common.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Common Namespace](microsoft-dynamics-retail-sharepoint-web-common-namespace.md)

