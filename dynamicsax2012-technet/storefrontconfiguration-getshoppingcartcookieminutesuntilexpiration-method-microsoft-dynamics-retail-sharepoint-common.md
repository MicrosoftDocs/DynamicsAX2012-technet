---
title: StorefrontConfiguration.GetShoppingCartCookieMinutesUntilExpiration Method  (Microsoft.Dynamics.Retail.SharePoint.Common)
TOCTitle: GetShoppingCartCookieMinutesUntilExpiration Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Common.StorefrontConfiguration.GetShoppingCartCookieMinutesUntilExpiration
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.common.storefrontconfiguration.getshoppingcartcookieminutesuntilexpiration(v=AX.60)
ms:contentKeyID: 62206464
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Common.StorefrontConfiguration.GetShoppingCartCookieMinutesUntilExpiration
dev_langs:
- CSharp
- C++
- VB
---

# GetShoppingCartCookieMinutesUntilExpiration Method

Gets the number of minutes until the shopping cart cookies expire.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Common](microsoft-dynamics-retail-sharepoint-common-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GetShoppingCartCookieMinutesUntilExpiration As Double
'Usage
Dim returnValue As Double

returnValue = StorefrontConfiguration.GetShoppingCartCookieMinutesUntilExpiration()
```

``` csharp
public static double GetShoppingCartCookieMinutesUntilExpiration()
```

``` c++
public:
static double GetShoppingCartCookieMinutesUntilExpiration()
```

#### Return Value

Type: [System.Double](https://technet.microsoft.com/library/643eft0t\(v=ax.60\))  
The time limit for expiration of shopping cart cookie.  

## See Also

#### Reference

[StorefrontConfiguration Class](storefrontconfiguration-class-microsoft-dynamics-retail-sharepoint-common.md)

[Microsoft.Dynamics.Retail.SharePoint.Common Namespace](microsoft-dynamics-retail-sharepoint-common-namespace.md)

