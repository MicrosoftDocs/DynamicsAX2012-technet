---
title: TrustedIdentityProviderSettingsFeatureEventReceiver.FeatureDeactivating Method  (Microsoft.Dynamics.Retail.SP.CommonFeatures.Features.TrustedIdentityProviderSettingsFeature)
TOCTitle: FeatureDeactivating Method
ms:assetid: M:Microsoft.Dynamics.Retail.SP.CommonFeatures.Features.TrustedIdentityProviderSettingsFeature.TrustedIdentityProviderSettingsFeatureEventReceiver.FeatureDeactivating(Microsoft.SharePoint.SPFeatureReceiverProperties)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sp.commonfeatures.features.trustedidentityprovidersettingsfeature.trustedidentityprovidersettingsfeatureeventreceiver.featuredeactivating(v=AX.60)
ms:contentKeyID: 62203016
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SP.CommonFeatures.Features.TrustedIdentityProviderSettingsFeature.TrustedIdentityProviderSettingsFeatureEventReceiver.FeatureDeactivating
dev_langs:
- CSharp
- C++
- VB
---

# FeatureDeactivating Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Handles the event that is raised after a Feature is deactivated.

**Namespace:**  [Microsoft.Dynamics.Retail.SP.CommonFeatures.Features.TrustedIdentityProviderSettingsFeature](microsoft-dynamics-retail-sp-commonfeatures-features-trustedidentityprovidersettingsfeature-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Storefront (in Microsoft.Dynamics.Retail.SP.Web.Storefront.dll)

## Syntax

``` vb
'Declaration
Public Overrides Sub FeatureDeactivating ( _
    properties As SPFeatureReceiverProperties _
)
'Usage
Dim instance As TrustedIdentityProviderSettingsFeatureEventReceiver
Dim properties As SPFeatureReceiverProperties

instance.FeatureDeactivating(properties)
```

``` csharp
public override void FeatureDeactivating(
    SPFeatureReceiverProperties properties
)
```

``` c++
public:
virtual void FeatureDeactivating(
    SPFeatureReceiverProperties^ properties
) override
```

#### Parameters

  - properties  
    Type: SPFeatureReceiverProperties  

## See Also

#### Reference

[TrustedIdentityProviderSettingsFeatureEventReceiver Class](trustedidentityprovidersettingsfeatureeventreceiver-class-microsoft-dynamics-retail-sp-commonfeatures-features-trustedidentityprovidersettingsfeature.md)

[Microsoft.Dynamics.Retail.SP.CommonFeatures.Features.TrustedIdentityProviderSettingsFeature Namespace](microsoft-dynamics-retail-sp-commonfeatures-features-trustedidentityprovidersettingsfeature-namespace.md)

