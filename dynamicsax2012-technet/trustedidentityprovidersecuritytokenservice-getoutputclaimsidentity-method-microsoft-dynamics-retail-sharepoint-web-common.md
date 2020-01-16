---
title: TrustedIdentityProviderSecurityTokenService.GetOutputClaimsIdentity Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Common)
TOCTitle: GetOutputClaimsIdentity Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Common.TrustedIdentityProviderSecurityTokenService.GetOutputClaimsIdentity(Microsoft.IdentityModel.Claims.IClaimsPrincipal,Microsoft.IdentityModel.Protocols.WSTrust.RequestSecurityToken,Microsoft.IdentityModel.SecurityTokenService.Scope)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.common.trustedidentityprovidersecuritytokenservice.getoutputclaimsidentity(v=AX.60)
ms:contentKeyID: 62206640
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Common.TrustedIdentityProviderSecurityTokenService.GetOutputClaimsIdentity
dev_langs:
- CSharp
- C++
- VB
---

# GetOutputClaimsIdentity Method

This method returns the claims to be issued in the token.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Common](microsoft-dynamics-retail-sharepoint-web-common-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Protected Overrides Function GetOutputClaimsIdentity ( _
    principal As IClaimsPrincipal, _
    request As RequestSecurityToken, _
    scope As Scope _
) As IClaimsIdentity
'Usage
Dim principal As IClaimsPrincipal
Dim request As RequestSecurityToken
Dim scope As Scope
Dim returnValue As IClaimsIdentity

returnValue = Me.GetOutputClaimsIdentity(principal, _
    request, scope)
```

``` csharp
protected override IClaimsIdentity GetOutputClaimsIdentity(
    IClaimsPrincipal principal,
    RequestSecurityToken request,
    Scope scope
)
```

``` c++
protected:
virtual IClaimsIdentity^ GetOutputClaimsIdentity(
    IClaimsPrincipal^ principal, 
    RequestSecurityToken^ request, 
    Scope^ scope
) override
```

#### Parameters

  - principal  
    Type: IClaimsPrincipal  

<!-- end list -->

  - request  
    Type: RequestSecurityToken  

<!-- end list -->

  - scope  
    Type: Scope  

#### Return Value

Type: IClaimsIdentity  
The outgoing claimsIdentity to be included in the issued token.  

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
<td><a href="https://technet.microsoft.com/library/27426hcy(v=ax.60)">ArgumentNullException</a></td>
<td><p>If 'principal' parameter is null.</p></td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[TrustedIdentityProviderSecurityTokenService Class](trustedidentityprovidersecuritytokenservice-class-microsoft-dynamics-retail-sharepoint-web-common.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Common Namespace](microsoft-dynamics-retail-sharepoint-web-common-namespace.md)

