---
title: TrustedIdentityProviderSecurityTokenService.GetScope Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Common)
TOCTitle: GetScope Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Common.TrustedIdentityProviderSecurityTokenService.GetScope(Microsoft.IdentityModel.Claims.IClaimsPrincipal,Microsoft.IdentityModel.Protocols.WSTrust.RequestSecurityToken)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.common.trustedidentityprovidersecuritytokenservice.getscope(v=AX.60)
ms:contentKeyID: 62205217
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Common.TrustedIdentityProviderSecurityTokenService.GetScope
dev_langs:
- CSharp
- C++
- VB
---

# GetScope Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

This method returns the configuration for the token issuance request. The configuration is represented by the Scope class. In our case, we are only capable of issuing a token for a single RP identity represented by the EncryptingCertificateName.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Common](microsoft-dynamics-retail-sharepoint-web-common-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Protected Overrides Function GetScope ( _
    principal As IClaimsPrincipal, _
    request As RequestSecurityToken _
) As Scope
'Usage
Dim principal As IClaimsPrincipal
Dim request As RequestSecurityToken
Dim returnValue As Scope

returnValue = Me.GetScope(principal, _
    request)
```

``` csharp
protected override Scope GetScope(
    IClaimsPrincipal principal,
    RequestSecurityToken request
)
```

``` c++
protected:
virtual Scope^ GetScope(
    IClaimsPrincipal^ principal, 
    RequestSecurityToken^ request
) override
```

#### Parameters

  - principal  
    Type: IClaimsPrincipal  

<!-- end list -->

  - request  
    Type: RequestSecurityToken  

#### Return Value

Type: Scope  
The scope information to be used for the token issuance.  

## See Also

#### Reference

[TrustedIdentityProviderSecurityTokenService Class](trustedidentityprovidersecuritytokenservice-class-microsoft-dynamics-retail-sharepoint-web-common.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Common Namespace](microsoft-dynamics-retail-sharepoint-web-common-namespace.md)

