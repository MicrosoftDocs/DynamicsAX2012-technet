---
title: UrlManager.GetReturnUrl Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Common)
TOCTitle: GetReturnUrl Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Common.UrlManager.GetReturnUrl
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.web.common.urlmanager.getreturnurl(v=AX.60)
ms:contentKeyID: 62204023
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Common.UrlManager.GetReturnUrl
dev_langs:
- CSharp
- C++
- VB
---

# GetReturnUrl Method

Gets the return url from the querystring or returns the site root url if not found.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Common](microsoft-dynamics-retail-sharepoint-web-common-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GetReturnUrl As String
'Usage
Dim returnValue As String

returnValue = UrlManager.GetReturnUrl()
```

``` csharp
public static string GetReturnUrl()
```

``` c++
public:
static String^ GetReturnUrl()
```

#### Return Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The return url.  

## See Also

#### Reference

[UrlManager Class](urlmanager-class-microsoft-dynamics-retail-sharepoint-web-common.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Common Namespace](microsoft-dynamics-retail-sharepoint-web-common-namespace.md)

