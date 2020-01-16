---
title: CommerceRuntimeSettingsFeatureEventReceiver.FeatureDeactivating Method  (Microsoft.Dynamics.Retail.SP.CommerceRuntime.Features.Settings)
TOCTitle: FeatureDeactivating Method
ms:assetid: M:Microsoft.Dynamics.Retail.SP.CommerceRuntime.Features.Settings.CommerceRuntimeSettingsFeatureEventReceiver.FeatureDeactivating(Microsoft.SharePoint.SPFeatureReceiverProperties)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sp.commerceruntime.features.settings.commerceruntimesettingsfeatureeventreceiver.featuredeactivating(v=AX.60)
ms:contentKeyID: 62202919
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SP.CommerceRuntime.Features.Settings.CommerceRuntimeSettingsFeatureEventReceiver.FeatureDeactivating
dev_langs:
- CSharp
- C++
- VB
---

# FeatureDeactivating Method

Handles the event that is raised when a Feature is deactivated.

**Namespace:**  [Microsoft.Dynamics.Retail.SP.CommerceRuntime.Features.Settings](microsoft-dynamics-retail-sp-commerceruntime-features-settings-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Storefront (in Microsoft.Dynamics.Retail.SP.Web.Storefront.dll)

## Syntax

``` vb
'Declaration
Public Overrides Sub FeatureDeactivating ( _
    properties As SPFeatureReceiverProperties _
)
'Usage
Dim instance As CommerceRuntimeSettingsFeatureEventReceiver
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

[CommerceRuntimeSettingsFeatureEventReceiver Class](commerceruntimesettingsfeatureeventreceiver-class-microsoft-dynamics-retail-sp-commerceruntime-features-settings.md)

[Microsoft.Dynamics.Retail.SP.CommerceRuntime.Features.Settings Namespace](microsoft-dynamics-retail-sp-commerceruntime-features-settings-namespace.md)

