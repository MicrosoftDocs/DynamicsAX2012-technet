---
title: UrlManager.GetAssociateUrl Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Common)
TOCTitle: GetAssociateUrl Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Common.UrlManager.GetAssociateUrl(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.common.urlmanager.getassociateurl(v=AX.60)
ms:contentKeyID: 62205238
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Common.UrlManager.GetAssociateUrl
dev_langs:
- CSharp
- C++
- VB
---

# GetAssociateUrl Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the Url for the Associate page.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Common](microsoft-dynamics-retail-sharepoint-web-common-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GetAssociateUrl ( _
    returnUrl As String _
) As String
'Usage
Dim returnUrl As String
Dim returnValue As String

returnValue = UrlManager.GetAssociateUrl(returnUrl)
```

``` csharp
public static string GetAssociateUrl(
    string returnUrl
)
```

``` c++
public:
static String^ GetAssociateUrl(
    String^ returnUrl
)
```

#### Parameters

  - returnUrl  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The url of the associate customer page.  

## See Also

#### Reference

[UrlManager Class](urlmanager-class-microsoft-dynamics-retail-sharepoint-web-common.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Common Namespace](microsoft-dynamics-retail-sharepoint-web-common-namespace.md)

