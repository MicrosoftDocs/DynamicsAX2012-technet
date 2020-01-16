---
title: CookieManager.GetRequestCookieValue Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Common)
TOCTitle: GetRequestCookieValue Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Common.CookieManager.GetRequestCookieValue(System.Web.HttpContext,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.common.cookiemanager.getrequestcookievalue(v=AX.60)
ms:contentKeyID: 62207679
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Common.CookieManager.GetRequestCookieValue
dev_langs:
- CSharp
- C++
- VB
---

# GetRequestCookieValue Method

Gets the specified cookie value from the request.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Common](microsoft-dynamics-retail-sharepoint-web-common-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GetRequestCookieValue ( _
    context As HttpContext, _
    cookieName As String _
) As String
'Usage
Dim context As HttpContext
Dim cookieName As String
Dim returnValue As String

returnValue = CookieManager.GetRequestCookieValue(context, _
    cookieName)
```

``` csharp
public static string GetRequestCookieValue(
    HttpContext context,
    string cookieName
)
```

``` c++
public:
static String^ GetRequestCookieValue(
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

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
a string containing the cookie value.  

## See Also

#### Reference

[CookieManager Class](cookiemanager-class-microsoft-dynamics-retail-sharepoint-web-common.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Common Namespace](microsoft-dynamics-retail-sharepoint-web-common-namespace.md)

