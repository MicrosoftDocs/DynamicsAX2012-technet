---
title: CustomClaimsProviderFeatureEventReceiver.FeatureActivated Method  (Microsoft.Dynamics.Retail.SharePoint.Web.CommonGlobalModules.Features.CustomClaimsProviderFeature)
TOCTitle: FeatureActivated Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.CommonGlobalModules.Features.CustomClaimsProviderFeature.CustomClaimsProviderFeatureEventReceiver.FeatureActivated(Microsoft.SharePoint.SPFeatureReceiverProperties)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.web.commonglobalmodules.features.customclaimsproviderfeature.customclaimsproviderfeatureeventreceiver.featureactivated(v=AX.60)
ms:contentKeyID: 62206385
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.CommonGlobalModules.Features.CustomClaimsProviderFeature.CustomClaimsProviderFeatureEventReceiver.FeatureActivated
dev_langs:
- CSharp
- C++
- VB
---

# FeatureActivated Method

Handles the event that is raised after a Feature is activated.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.CommonGlobalModules.Features.CustomClaimsProviderFeature](microsoft-dynamics-retail-sharepoint-web-commonglobalmodules-features-customclaimsproviderfeature-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.CommonGlobalModules (in Microsoft.Dynamics.Retail.SP.Web.CommonGlobalModules.dll)

## Syntax

``` vb
'Declaration
Public Overrides Sub FeatureActivated ( _
    properties As SPFeatureReceiverProperties _
)
'Usage
Dim instance As CustomClaimsProviderFeatureEventReceiver
Dim properties As SPFeatureReceiverProperties

instance.FeatureActivated(properties)
```

``` csharp
public override void FeatureActivated(
    SPFeatureReceiverProperties properties
)
```

``` c++
public:
virtual void FeatureActivated(
    SPFeatureReceiverProperties^ properties
) override
```

#### Parameters

  - properties  
    Type: SPFeatureReceiverProperties  

## See Also

#### Reference

[CustomClaimsProviderFeatureEventReceiver Class](customclaimsproviderfeatureeventreceiver-class-microsoft-dynamics-retail-sharepoint-web-commonglobalmodules-features-customclaimsproviderfeature.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.CommonGlobalModules.Features.CustomClaimsProviderFeature Namespace](microsoft-dynamics-retail-sharepoint-web-commonglobalmodules-features-customclaimsproviderfeature-namespace.md)

