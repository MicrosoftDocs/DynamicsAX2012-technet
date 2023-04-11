---
title: CookieManager.ClearResponseCookies Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Common)
TOCTitle: ClearResponseCookies Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Common.CookieManager.ClearResponseCookies(System.Web.HttpContext)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.common.cookiemanager.clearresponsecookies(v=AX.60)
ms:contentKeyID: 62205072
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Common.CookieManager.ClearResponseCookies
dev_langs:
- CSharp
- C++
- VB
---

# ClearResponseCookies Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Clear all cookes.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Common](microsoft-dynamics-retail-sharepoint-web-common-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Shared Sub ClearResponseCookies ( _
    context As HttpContext _
)
'Usage
Dim context As HttpContext

CookieManager.ClearResponseCookies(context)
```

``` csharp
public static void ClearResponseCookies(
    HttpContext context
)
```

``` c++
public:
static void ClearResponseCookies(
    HttpContext^ context
)
```

#### Parameters

  - context  
    Type: [System.Web.HttpContext](https://technet.microsoft.com/library/x08ey989\(v=ax.60\))  

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
<td><a href="cookieexception-class-microsoft-dynamics-retail-sharepoint-web-common.md">CookieException</a></td>
<td><p></p></td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[CookieManager Class](cookiemanager-class-microsoft-dynamics-retail-sharepoint-web-common.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Common Namespace](microsoft-dynamics-retail-sharepoint-web-common-namespace.md)

