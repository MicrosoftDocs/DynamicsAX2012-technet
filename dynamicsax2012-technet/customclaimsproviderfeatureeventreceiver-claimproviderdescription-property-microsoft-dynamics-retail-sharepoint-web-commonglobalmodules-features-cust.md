---
title: CustomClaimsProviderFeatureEventReceiver.ClaimProviderDescription Property  (Microsoft.Dynamics.Retail.SharePoint.Web.CommonGlobalModules.Features.CustomClaimsProviderFeature)
TOCTitle: ClaimProviderDescription Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.CommonGlobalModules.Features.CustomClaimsProviderFeature.CustomClaimsProviderFeatureEventReceiver.ClaimProviderDescription
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.web.commonglobalmodules.features.customclaimsproviderfeature.customclaimsproviderfeatureeventreceiver.claimproviderdescription(v=AX.60)
ms:contentKeyID: 62203570
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.CommonGlobalModules.Features.CustomClaimsProviderFeature.CustomClaimsProviderFeatureEventReceiver.ClaimProviderDescription
dev_langs:
- CSharp
- C++
- VB
---

# ClaimProviderDescription Property

Gets the description of the claims provider.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.CommonGlobalModules.Features.CustomClaimsProviderFeature](microsoft-dynamics-retail-sharepoint-web-commonglobalmodules-features-customclaimsproviderfeature-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.CommonGlobalModules (in Microsoft.Dynamics.Retail.SP.Web.CommonGlobalModules.dll)

## Syntax

``` vb
'Declaration
Public Overrides ReadOnly Property ClaimProviderDescription As String
    Get
'Usage
Dim instance As CustomClaimsProviderFeatureEventReceiver
Dim value As String

value = instance.ClaimProviderDescription
```

``` csharp
public override string ClaimProviderDescription { get; }
```

``` c++
public:
virtual property String^ ClaimProviderDescription {
    String^ get () override;
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[CustomClaimsProviderFeatureEventReceiver Class](customclaimsproviderfeatureeventreceiver-class-microsoft-dynamics-retail-sharepoint-web-commonglobalmodules-features-customclaimsproviderfeature.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.CommonGlobalModules.Features.CustomClaimsProviderFeature Namespace](microsoft-dynamics-retail-sharepoint-web-commonglobalmodules-features-customclaimsproviderfeature-namespace.md)

