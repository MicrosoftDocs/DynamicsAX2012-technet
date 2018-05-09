---
title: TrustedIdentityProviderSettingsFeatureEventReceiver.FeatureActivated Method  (Microsoft.Dynamics.Retail.SP.CommonFeatures.Features.TrustedIdentityProviderSettingsFeature)
TOCTitle: FeatureActivated Method
ms:assetid: M:Microsoft.Dynamics.Retail.SP.CommonFeatures.Features.TrustedIdentityProviderSettingsFeature.TrustedIdentityProviderSettingsFeatureEventReceiver.FeatureActivated(Microsoft.SharePoint.SPFeatureReceiverProperties)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sp.commonfeatures.features.trustedidentityprovidersettingsfeature.trustedidentityprovidersettingsfeatureeventreceiver.featureactivated(v=AX.60)
ms:contentKeyID: 62203280
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SP.CommonFeatures.Features.TrustedIdentityProviderSettingsFeature.TrustedIdentityProviderSettingsFeatureEventReceiver.FeatureActivated
dev_langs:
- CSharp
- C++
- VB
---

# FeatureActivated Method

Handles the event that is raised after a Feature is activated.

**Namespace:**  [Microsoft.Dynamics.Retail.SP.CommonFeatures.Features.TrustedIdentityProviderSettingsFeature](microsoft-dynamics-retail-sp-commonfeatures-features-trustedidentityprovidersettingsfeature-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Storefront (in Microsoft.Dynamics.Retail.SP.Web.Storefront.dll)

## Syntax

``` vb
'Declaration
Public Overrides Sub FeatureActivated ( _
    properties As SPFeatureReceiverProperties _
)
'Usage
Dim instance As TrustedIdentityProviderSettingsFeatureEventReceiver
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

[TrustedIdentityProviderSettingsFeatureEventReceiver Class](trustedidentityprovidersettingsfeatureeventreceiver-class-microsoft-dynamics-retail-sp-commonfeatures-features-trustedidentityprovidersettingsfeature.md)

[Microsoft.Dynamics.Retail.SP.CommonFeatures.Features.TrustedIdentityProviderSettingsFeature Namespace](microsoft-dynamics-retail-sp-commonfeatures-features-trustedidentityprovidersettingsfeature-namespace.md)

