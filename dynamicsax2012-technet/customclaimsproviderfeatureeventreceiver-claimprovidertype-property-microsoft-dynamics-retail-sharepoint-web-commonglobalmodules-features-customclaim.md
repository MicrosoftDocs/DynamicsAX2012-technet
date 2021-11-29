---
title: CustomClaimsProviderFeatureEventReceiver.ClaimProviderType Property  (Microsoft.Dynamics.Retail.SharePoint.Web.CommonGlobalModules.Features.CustomClaimsProviderFeature)
TOCTitle: ClaimProviderType Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.CommonGlobalModules.Features.CustomClaimsProviderFeature.CustomClaimsProviderFeatureEventReceiver.ClaimProviderType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.commonglobalmodules.features.customclaimsproviderfeature.customclaimsproviderfeatureeventreceiver.claimprovidertype(v=AX.60)
ms:contentKeyID: 62202916
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.CommonGlobalModules.Features.CustomClaimsProviderFeature.CustomClaimsProviderFeatureEventReceiver.ClaimProviderType
dev_langs:
- CSharp
- C++
- VB
---

# ClaimProviderType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the type for the claims hierarchy provider.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.CommonGlobalModules.Features.CustomClaimsProviderFeature](microsoft-dynamics-retail-sharepoint-web-commonglobalmodules-features-customclaimsproviderfeature-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.CommonGlobalModules (in Microsoft.Dynamics.Retail.SP.Web.CommonGlobalModules.dll)

## Syntax

``` vb
'Declaration
Public Overrides ReadOnly Property ClaimProviderType As String
    Get
'Usage
Dim instance As CustomClaimsProviderFeatureEventReceiver
Dim value As String

value = instance.ClaimProviderType
```

``` csharp
public override string ClaimProviderType { get; }
```

``` c++
public:
virtual property String^ ClaimProviderType {
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

