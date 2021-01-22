---
title: CustomClaimsProviderFeatureEventReceiver.ClaimProviderAssembly Property  (Microsoft.Dynamics.Retail.SharePoint.Web.CommonGlobalModules.Features.CustomClaimsProviderFeature)
TOCTitle: ClaimProviderAssembly Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.CommonGlobalModules.Features.CustomClaimsProviderFeature.CustomClaimsProviderFeatureEventReceiver.ClaimProviderAssembly
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.commonglobalmodules.features.customclaimsproviderfeature.customclaimsproviderfeatureeventreceiver.claimproviderassembly(v=AX.60)
ms:contentKeyID: 62204448
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.CommonGlobalModules.Features.CustomClaimsProviderFeature.CustomClaimsProviderFeatureEventReceiver.ClaimProviderAssembly
dev_langs:
- CSharp
- C++
- VB
---

# ClaimProviderAssembly Property

Gets the name of the assembly that contains the claims provider.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.CommonGlobalModules.Features.CustomClaimsProviderFeature](microsoft-dynamics-retail-sharepoint-web-commonglobalmodules-features-customclaimsproviderfeature-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.CommonGlobalModules (in Microsoft.Dynamics.Retail.SP.Web.CommonGlobalModules.dll)

## Syntax

``` vb
'Declaration
Public Overrides ReadOnly Property ClaimProviderAssembly As String
    Get
'Usage
Dim instance As CustomClaimsProviderFeatureEventReceiver
Dim value As String

value = instance.ClaimProviderAssembly
```

``` csharp
public override string ClaimProviderAssembly { get; }
```

``` c++
public:
virtual property String^ ClaimProviderAssembly {
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

