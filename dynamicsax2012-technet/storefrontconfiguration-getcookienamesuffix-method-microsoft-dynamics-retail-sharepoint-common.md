---
title: StorefrontConfiguration.GetCookieNameSuffix Method  (Microsoft.Dynamics.Retail.SharePoint.Common)
TOCTitle: GetCookieNameSuffix Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Common.StorefrontConfiguration.GetCookieNameSuffix
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.common.storefrontconfiguration.getcookienamesuffix(v=AX.60)
ms:contentKeyID: 62205214
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Common.StorefrontConfiguration.GetCookieNameSuffix
dev_langs:
- CSharp
- C++
- VB
---

# GetCookieNameSuffix Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The cookie name suffix is used to provide isolation between cookies of multiple storefronts on the same domain.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Common](microsoft-dynamics-retail-sharepoint-common-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GetCookieNameSuffix As String
'Usage
Dim returnValue As String

returnValue = StorefrontConfiguration.GetCookieNameSuffix()
```

``` csharp
public static string GetCookieNameSuffix()
```

``` c++
public:
static String^ GetCookieNameSuffix()
```

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The cookie name suffix.  

## See Also

#### Reference

[StorefrontConfiguration Class](storefrontconfiguration-class-microsoft-dynamics-retail-sharepoint-common.md)

[Microsoft.Dynamics.Retail.SharePoint.Common Namespace](microsoft-dynamics-retail-sharepoint-common-namespace.md)

