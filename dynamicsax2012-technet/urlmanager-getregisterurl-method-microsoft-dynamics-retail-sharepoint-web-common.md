---
title: UrlManager.GetRegisterUrl Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Common)
TOCTitle: GetRegisterUrl Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Common.UrlManager.GetRegisterUrl(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.common.urlmanager.getregisterurl(v=AX.60)
ms:contentKeyID: 62204314
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Common.UrlManager.GetRegisterUrl
dev_langs:
- CSharp
- C++
- VB
---

# GetRegisterUrl Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the Url for the Register page.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Common](microsoft-dynamics-retail-sharepoint-web-common-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GetRegisterUrl ( _
    returnUrl As String _
) As String
'Usage
Dim returnUrl As String
Dim returnValue As String

returnValue = UrlManager.GetRegisterUrl(returnUrl)
```

``` csharp
public static string GetRegisterUrl(
    string returnUrl
)
```

``` c++
public:
static String^ GetRegisterUrl(
    String^ returnUrl
)
```

#### Parameters

  - returnUrl  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The url of the registration page.  

## See Also

#### Reference

[UrlManager Class](urlmanager-class-microsoft-dynamics-retail-sharepoint-web-common.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Common Namespace](microsoft-dynamics-retail-sharepoint-web-common-namespace.md)

