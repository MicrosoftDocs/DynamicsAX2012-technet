---
title: CustomClaimsProviderSettingsFeatureEventReceiver.FeatureActivated Method  (Microsoft.Dynamics.Retail.SharePoint.CommonFeatures.CustomClaimsProviderSettingsFeature)
TOCTitle: FeatureActivated Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.CommonFeatures.CustomClaimsProviderSettingsFeature.CustomClaimsProviderSettingsFeatureEventReceiver.FeatureActivated(Microsoft.SharePoint.SPFeatureReceiverProperties)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.commonfeatures.customclaimsprovidersettingsfeature.customclaimsprovidersettingsfeatureeventreceiver.featureactivated(v=AX.60)
ms:contentKeyID: 62207569
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.CommonFeatures.CustomClaimsProviderSettingsFeature.CustomClaimsProviderSettingsFeatureEventReceiver.FeatureActivated
dev_langs:
- CSharp
- C++
- VB
---

# FeatureActivated Method

Handles the event that is raised after a Feature is activated.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.CommonFeatures.CustomClaimsProviderSettingsFeature](microsoft-dynamics-retail-sharepoint-commonfeatures-customclaimsprovidersettingsfeature-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Storefront (in Microsoft.Dynamics.Retail.SP.Web.Storefront.dll)

## Syntax

``` vb
'Declaration
Public Overrides Sub FeatureActivated ( _
    properties As SPFeatureReceiverProperties _
)
'Usage
Dim instance As CustomClaimsProviderSettingsFeatureEventReceiver
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

[CustomClaimsProviderSettingsFeatureEventReceiver Class](customclaimsprovidersettingsfeatureeventreceiver-class-microsoft-dynamics-retail-sharepoint-commonfeatures-customclaimsprovidersettingsfeature.md)

[Microsoft.Dynamics.Retail.SharePoint.CommonFeatures.CustomClaimsProviderSettingsFeature Namespace](microsoft-dynamics-retail-sharepoint-commonfeatures-customclaimsprovidersettingsfeature-namespace.md)

