---
title: CustomClaimsProviderSettingsFeatureEventReceiver.FeatureDeactivating Method  (Microsoft.Dynamics.Retail.SharePoint.CommonFeatures.CustomClaimsProviderSettingsFeature)
TOCTitle: FeatureDeactivating Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.CommonFeatures.CustomClaimsProviderSettingsFeature.CustomClaimsProviderSettingsFeatureEventReceiver.FeatureDeactivating(Microsoft.SharePoint.SPFeatureReceiverProperties)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.commonfeatures.customclaimsprovidersettingsfeature.customclaimsprovidersettingsfeatureeventreceiver.featuredeactivating(v=AX.60)
ms:contentKeyID: 62203329
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.CommonFeatures.CustomClaimsProviderSettingsFeature.CustomClaimsProviderSettingsFeatureEventReceiver.FeatureDeactivating
dev_langs:
- CSharp
- C++
- VB
---

# FeatureDeactivating Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Handles the event that is raised when a Feature is deactivated.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.CommonFeatures.CustomClaimsProviderSettingsFeature](microsoft-dynamics-retail-sharepoint-commonfeatures-customclaimsprovidersettingsfeature-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Storefront (in Microsoft.Dynamics.Retail.SP.Web.Storefront.dll)

## Syntax

``` vb
'Declaration
Public Overrides Sub FeatureDeactivating ( _
    properties As SPFeatureReceiverProperties _
)
'Usage
Dim instance As CustomClaimsProviderSettingsFeatureEventReceiver
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

[CustomClaimsProviderSettingsFeatureEventReceiver Class](customclaimsprovidersettingsfeatureeventreceiver-class-microsoft-dynamics-retail-sharepoint-commonfeatures-customclaimsprovidersettingsfeature.md)

[Microsoft.Dynamics.Retail.SharePoint.CommonFeatures.CustomClaimsProviderSettingsFeature Namespace](microsoft-dynamics-retail-sharepoint-commonfeatures-customclaimsprovidersettingsfeature-namespace.md)

