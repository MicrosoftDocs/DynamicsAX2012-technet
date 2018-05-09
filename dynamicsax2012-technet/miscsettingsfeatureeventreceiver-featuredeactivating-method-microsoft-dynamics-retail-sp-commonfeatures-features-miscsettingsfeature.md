---
title: MiscSettingsFeatureEventReceiver.FeatureDeactivating Method  (Microsoft.Dynamics.Retail.SP.CommonFeatures.Features.MiscSettingsFeature)
TOCTitle: FeatureDeactivating Method
ms:assetid: M:Microsoft.Dynamics.Retail.SP.CommonFeatures.Features.MiscSettingsFeature.MiscSettingsFeatureEventReceiver.FeatureDeactivating(Microsoft.SharePoint.SPFeatureReceiverProperties)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sp.commonfeatures.features.miscsettingsfeature.miscsettingsfeatureeventreceiver.featuredeactivating(v=AX.60)
ms:contentKeyID: 62201857
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SP.CommonFeatures.Features.MiscSettingsFeature.MiscSettingsFeatureEventReceiver.FeatureDeactivating
dev_langs:
- CSharp
- C++
- VB
---

# FeatureDeactivating Method

Handles the event that is raised after a Feature is deactivated.

**Namespace:**  [Microsoft.Dynamics.Retail.SP.CommonFeatures.Features.MiscSettingsFeature](microsoft-dynamics-retail-sp-commonfeatures-features-miscsettingsfeature-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Storefront (in Microsoft.Dynamics.Retail.SP.Web.Storefront.dll)

## Syntax

``` vb
'Declaration
Public Overrides Sub FeatureDeactivating ( _
    properties As SPFeatureReceiverProperties _
)
'Usage
Dim instance As MiscSettingsFeatureEventReceiver
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

[MiscSettingsFeatureEventReceiver Class](miscsettingsfeatureeventreceiver-class-microsoft-dynamics-retail-sp-commonfeatures-features-miscsettingsfeature.md)

[Microsoft.Dynamics.Retail.SP.CommonFeatures.Features.MiscSettingsFeature Namespace](microsoft-dynamics-retail-sp-commonfeatures-features-miscsettingsfeature-namespace.md)

