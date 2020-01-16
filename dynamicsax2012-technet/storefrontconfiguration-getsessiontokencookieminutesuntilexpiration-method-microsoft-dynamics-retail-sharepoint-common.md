---
title: StorefrontConfiguration.GetSessionTokenCookieMinutesUntilExpiration Method  (Microsoft.Dynamics.Retail.SharePoint.Common)
TOCTitle: GetSessionTokenCookieMinutesUntilExpiration Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Common.StorefrontConfiguration.GetSessionTokenCookieMinutesUntilExpiration
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.common.storefrontconfiguration.getsessiontokencookieminutesuntilexpiration(v=AX.60)
ms:contentKeyID: 62202473
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Common.StorefrontConfiguration.GetSessionTokenCookieMinutesUntilExpiration
dev_langs:
- CSharp
- C++
- VB
---

# GetSessionTokenCookieMinutesUntilExpiration Method

Gets the number of minutes until the session token cookie is expired.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Common](microsoft-dynamics-retail-sharepoint-common-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GetSessionTokenCookieMinutesUntilExpiration As Double
'Usage
Dim returnValue As Double

returnValue = StorefrontConfiguration.GetSessionTokenCookieMinutesUntilExpiration()
```

``` csharp
public static double GetSessionTokenCookieMinutesUntilExpiration()
```

``` c++
public:
static double GetSessionTokenCookieMinutesUntilExpiration()
```

#### Return Value

Type: [System.Double](https://technet.microsoft.com/library/643eft0t\(v=ax.60\))  
The time limit for expiration of session token cookie.  

## See Also

#### Reference

[StorefrontConfiguration Class](storefrontconfiguration-class-microsoft-dynamics-retail-sharepoint-common.md)

[Microsoft.Dynamics.Retail.SharePoint.Common Namespace](microsoft-dynamics-retail-sharepoint-common-namespace.md)

