---
title: CustomClaimsProviderFeatureEventReceiver.ClaimProviderDisplayName Property  (Microsoft.Dynamics.Retail.SharePoint.Web.CommonGlobalModules.Features.CustomClaimsProviderFeature)
TOCTitle: ClaimProviderDisplayName Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.CommonGlobalModules.Features.CustomClaimsProviderFeature.CustomClaimsProviderFeatureEventReceiver.ClaimProviderDisplayName
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.commonglobalmodules.features.customclaimsproviderfeature.customclaimsproviderfeatureeventreceiver.claimproviderdisplayname(v=AX.60)
ms:contentKeyID: 62205668
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.CommonGlobalModules.Features.CustomClaimsProviderFeature.CustomClaimsProviderFeatureEventReceiver.ClaimProviderDisplayName
dev_langs:
- CSharp
- C++
- VB
---

# ClaimProviderDisplayName Property

Gets the display name of the claims provider.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.CommonGlobalModules.Features.CustomClaimsProviderFeature](microsoft-dynamics-retail-sharepoint-web-commonglobalmodules-features-customclaimsproviderfeature-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.CommonGlobalModules (in Microsoft.Dynamics.Retail.SP.Web.CommonGlobalModules.dll)

## Syntax

``` vb
'Declaration
Public Overrides ReadOnly Property ClaimProviderDisplayName As String
    Get
'Usage
Dim instance As CustomClaimsProviderFeatureEventReceiver
Dim value As String

value = instance.ClaimProviderDisplayName
```

``` csharp
public override string ClaimProviderDisplayName { get; }
```

``` c++
public:
virtual property String^ ClaimProviderDisplayName {
    String^ get () override;
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[CustomClaimsProviderFeatureEventReceiver Class](customclaimsproviderfeatureeventreceiver-class-microsoft-dynamics-retail-sharepoint-web-commonglobalmodules-features-customclaimsproviderfeature.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.CommonGlobalModules.Features.CustomClaimsProviderFeature Namespace](microsoft-dynamics-retail-sharepoint-web-commonglobalmodules-features-customclaimsproviderfeature-namespace.md)

