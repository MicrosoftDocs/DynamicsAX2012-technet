---
title: TrustedIdentityProviderSecurityTokenService Constructor  (Microsoft.Dynamics.Retail.SharePoint.Web.Common)
TOCTitle: TrustedIdentityProviderSecurityTokenService Constructor
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Common.TrustedIdentityProviderSecurityTokenService.#ctor(Microsoft.IdentityModel.Configuration.SecurityTokenServiceConfiguration,Microsoft.IdentityModel.Claims.ClaimsIdentity)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.common.trustedidentityprovidersecuritytokenservice.trustedidentityprovidersecuritytokenservice(v=AX.60)
ms:contentKeyID: 62202707
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Common.TrustedIdentityProviderSecurityTokenService.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# TrustedIdentityProviderSecurityTokenService Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Creates an instance of TrustedIdentityProviderSecurityTokenService.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Common](microsoft-dynamics-retail-sharepoint-web-common-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    configuration As SecurityTokenServiceConfiguration, _
    claimsIdentity As ClaimsIdentity _
)
'Usage
Dim configuration As SecurityTokenServiceConfiguration
Dim claimsIdentity As ClaimsIdentity

Dim instance As New TrustedIdentityProviderSecurityTokenService(configuration, _
    claimsIdentity)
```

``` csharp
public TrustedIdentityProviderSecurityTokenService(
    SecurityTokenServiceConfiguration configuration,
    ClaimsIdentity claimsIdentity
)
```

``` c++
public:
TrustedIdentityProviderSecurityTokenService(
    SecurityTokenServiceConfiguration^ configuration, 
    ClaimsIdentity^ claimsIdentity
)
```

#### Parameters

  - configuration  
    Type: SecurityTokenServiceConfiguration  

<!-- end list -->

  - claimsIdentity  
    Type: ClaimsIdentity  

## See Also

#### Reference

[TrustedIdentityProviderSecurityTokenService Class](trustedidentityprovidersecuritytokenservice-class-microsoft-dynamics-retail-sharepoint-web-common.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Common Namespace](microsoft-dynamics-retail-sharepoint-web-common-namespace.md)

