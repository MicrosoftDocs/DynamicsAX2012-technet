---
title: DebugSettingsFeatureEventReceiver.FeatureDeactivating Method  (Microsoft.Dynamics.Retail.SharePoint.CommonFeatures.DebugSettingsFeature)
TOCTitle: FeatureDeactivating Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.CommonFeatures.DebugSettingsFeature.DebugSettingsFeatureEventReceiver.FeatureDeactivating(Microsoft.SharePoint.SPFeatureReceiverProperties)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.commonfeatures.debugsettingsfeature.debugsettingsfeatureeventreceiver.featuredeactivating(v=AX.60)
ms:contentKeyID: 62205244
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.CommonFeatures.DebugSettingsFeature.DebugSettingsFeatureEventReceiver.FeatureDeactivating
dev_langs:
- CSharp
- C++
- VB
---

# FeatureDeactivating Method

Handles the event that is raised when a Feature is deactivated.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.CommonFeatures.DebugSettingsFeature](microsoft-dynamics-retail-sharepoint-commonfeatures-debugsettingsfeature-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Storefront (in Microsoft.Dynamics.Retail.SP.Web.Storefront.dll)

## Syntax

``` vb
'Declaration
Public Overrides Sub FeatureDeactivating ( _
    properties As SPFeatureReceiverProperties _
)
'Usage
Dim instance As DebugSettingsFeatureEventReceiver
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

[DebugSettingsFeatureEventReceiver Class](debugsettingsfeatureeventreceiver-class-microsoft-dynamics-retail-sharepoint-commonfeatures-debugsettingsfeature.md)

[Microsoft.Dynamics.Retail.SharePoint.CommonFeatures.DebugSettingsFeature Namespace](microsoft-dynamics-retail-sharepoint-commonfeatures-debugsettingsfeature-namespace.md)

