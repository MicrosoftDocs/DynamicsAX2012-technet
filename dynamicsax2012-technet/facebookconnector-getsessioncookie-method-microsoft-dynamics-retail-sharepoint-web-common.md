---
title: FacebookConnector.GetSessionCookie Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Common)
TOCTitle: GetSessionCookie Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Common.FacebookConnector.GetSessionCookie(System.Web.HttpCookieCollection)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.common.facebookconnector.getsessioncookie(v=AX.60)
ms:contentKeyID: 62204906
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Common.FacebookConnector.GetSessionCookie
dev_langs:
- CSharp
- C++
- VB
---

# GetSessionCookie Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the session cookie.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Common](microsoft-dynamics-retail-sharepoint-web-common-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Function GetSessionCookie ( _
    cookies As HttpCookieCollection _
) As FacebookSessionCookie
'Usage
Dim instance As FacebookConnector
Dim cookies As HttpCookieCollection
Dim returnValue As FacebookSessionCookie

returnValue = instance.GetSessionCookie(cookies)
```

``` csharp
public FacebookSessionCookie GetSessionCookie(
    HttpCookieCollection cookies
)
```

``` c++
public:
FacebookSessionCookie^ GetSessionCookie(
    HttpCookieCollection^ cookies
)
```

#### Parameters

  - cookies  
    Type: [System.Web.HttpCookieCollection](https://technet.microsoft.com/library/w6hha0ef\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Common.FacebookSessionCookie](facebooksessioncookie-class-microsoft-dynamics-retail-sharepoint-web-common.md)  
A Facebook session cookie.  

## See Also

#### Reference

[FacebookConnector Class](facebookconnector-class-microsoft-dynamics-retail-sharepoint-web-common.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Common Namespace](microsoft-dynamics-retail-sharepoint-web-common-namespace.md)

