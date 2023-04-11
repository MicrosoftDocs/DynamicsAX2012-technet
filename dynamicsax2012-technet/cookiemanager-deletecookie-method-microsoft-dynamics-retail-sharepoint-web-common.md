---
title: CookieManager.DeleteCookie Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Common)
TOCTitle: DeleteCookie Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Common.CookieManager.DeleteCookie(System.Web.HttpContext,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.common.cookiemanager.deletecookie(v=AX.60)
ms:contentKeyID: 62205833
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Common.CookieManager.DeleteCookie
dev_langs:
- CSharp
- C++
- VB
---

# DeleteCookie Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Expire the cookie with the specified cookie name in the response.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Common](microsoft-dynamics-retail-sharepoint-web-common-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Shared Sub DeleteCookie ( _
    context As HttpContext, _
    cookieName As String _
)
'Usage
Dim context As HttpContext
Dim cookieName As String

CookieManager.DeleteCookie(context, cookieName)
```

``` csharp
public static void DeleteCookie(
    HttpContext context,
    string cookieName
)
```

``` c++
public:
static void DeleteCookie(
    HttpContext^ context, 
    String^ cookieName
)
```

#### Parameters

  - context  
    Type: [System.Web.HttpContext](https://technet.microsoft.com/library/x08ey989\(v=ax.60\))  

<!-- end list -->

  - cookieName  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[CookieManager Class](cookiemanager-class-microsoft-dynamics-retail-sharepoint-web-common.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Common Namespace](microsoft-dynamics-retail-sharepoint-web-common-namespace.md)

