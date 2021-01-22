---
title: CookieManager.SetResponseCookieValue Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Common)
TOCTitle: SetResponseCookieValue Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Common.CookieManager.SetResponseCookieValue(System.Web.HttpContext,System.String,System.String,System.DateTime,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.common.cookiemanager.setresponsecookievalue(v=AX.60)
ms:contentKeyID: 62207146
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Common.CookieManager.SetResponseCookieValue
dev_langs:
- CSharp
- C++
- VB
---

# SetResponseCookieValue Method

Sets the cookie value with the specified cookie name in the response.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Common](microsoft-dynamics-retail-sharepoint-web-common-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Shared Sub SetResponseCookieValue ( _
    context As HttpContext, _
    cookieName As String, _
    cookieValue As String, _
    expiry As DateTime, _
    isSecure As Boolean _
)
'Usage
Dim context As HttpContext
Dim cookieName As String
Dim cookieValue As String
Dim expiry As DateTime
Dim isSecure As Boolean

CookieManager.SetResponseCookieValue(context, _
    cookieName, cookieValue, expiry, _
    isSecure)
```

``` csharp
public static void SetResponseCookieValue(
    HttpContext context,
    string cookieName,
    string cookieValue,
    DateTime expiry,
    bool isSecure
)
```

``` c++
public:
static void SetResponseCookieValue(
    HttpContext^ context, 
    String^ cookieName, 
    String^ cookieValue, 
    DateTime expiry, 
    bool isSecure
)
```

#### Parameters

  - context  
    Type: [System.Web.HttpContext](https://technet.microsoft.com/library/x08ey989\(v=ax.60\))  

<!-- end list -->

  - cookieName  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - cookieValue  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - expiry  
    Type: [System.DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\))  

<!-- end list -->

  - isSecure  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## Exceptions

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>Exception</th>
<th>Condition</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><a href="https://technet.microsoft.com/library/3w1b3114(v=ax.60)">ArgumentException</a></td>
<td><p>The cookie name cannot be null or contain white space only.</p>
<p>-or-</p>
<p>ArgumentException is thrown when invalid cookie name is specified.</p></td>
</tr>
<tr class="even">
<td><a href="cookieexception-class-microsoft-dynamics-retail-sharepoint-web-common.md">CookieException</a></td>
<td><p></p></td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[CookieManager Class](cookiemanager-class-microsoft-dynamics-retail-sharepoint-web-common.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Common Namespace](microsoft-dynamics-retail-sharepoint-web-common-namespace.md)

