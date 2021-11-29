---
title: SharePointTraceListenerSettingsFeatureEventReceiver.FeatureDeactivating Method  (Microsoft.Dynamics.Retail.SP.CommonFeatures.Features.SharePointTraceListenerSettingsFeature)
TOCTitle: FeatureDeactivating Method
ms:assetid: M:Microsoft.Dynamics.Retail.SP.CommonFeatures.Features.SharePointTraceListenerSettingsFeature.SharePointTraceListenerSettingsFeatureEventReceiver.FeatureDeactivating(Microsoft.SharePoint.SPFeatureReceiverProperties)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sp.commonfeatures.features.sharepointtracelistenersettingsfeature.sharepointtracelistenersettingsfeatureeventreceiver.featuredeactivating(v=AX.60)
ms:contentKeyID: 62204495
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SP.CommonFeatures.Features.SharePointTraceListenerSettingsFeature.SharePointTraceListenerSettingsFeatureEventReceiver.FeatureDeactivating
dev_langs:
- CSharp
- C++
- VB
---

# FeatureDeactivating Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Handles the event that is raised when a Feature is deactivated.

**Namespace:**  [Microsoft.Dynamics.Retail.SP.CommonFeatures.Features.SharePointTraceListenerSettingsFeature](microsoft-dynamics-retail-sp-commonfeatures-features-sharepointtracelistenersettingsfeature-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Storefront (in Microsoft.Dynamics.Retail.SP.Web.Storefront.dll)

## Syntax

``` vb
'Declaration
Public Overrides Sub FeatureDeactivating ( _
    properties As SPFeatureReceiverProperties _
)
'Usage
Dim instance As SharePointTraceListenerSettingsFeatureEventReceiver
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

[SharePointTraceListenerSettingsFeatureEventReceiver Class](sharepointtracelistenersettingsfeatureeventreceiver-class-microsoft-dynamics-retail-sp-commonfeatures-features-sharepointtracelistenersettingsfeature.md)

[Microsoft.Dynamics.Retail.SP.CommonFeatures.Features.SharePointTraceListenerSettingsFeature Namespace](microsoft-dynamics-retail-sp-commonfeatures-features-sharepointtracelistenersettingsfeature-namespace.md)

