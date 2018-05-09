---
title: UrlManager.GetLoginUrl Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Common)
TOCTitle: GetLoginUrl Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Common.UrlManager.GetLoginUrl(System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.web.common.urlmanager.getloginurl(v=AX.60)
ms:contentKeyID: 62207512
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Common.UrlManager.GetLoginUrl
dev_langs:
- CSharp
- C++
- VB
---

# GetLoginUrl Method

Gets the Login url.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Common](microsoft-dynamics-retail-sharepoint-web-common-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GetLoginUrl ( _
    returnUrl As String _
) As String
'Usage
Dim returnUrl As String
Dim returnValue As String

returnValue = UrlManager.GetLoginUrl(returnUrl)
```

``` csharp
public static string GetLoginUrl(
    string returnUrl
)
```

``` c++
public:
static String^ GetLoginUrl(
    String^ returnUrl
)
```

#### Parameters

  - returnUrl  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The login url.  

## See Also

#### Reference

[UrlManager Class](urlmanager-class-microsoft-dynamics-retail-sharepoint-web-common.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Common Namespace](microsoft-dynamics-retail-sharepoint-web-common-namespace.md)

