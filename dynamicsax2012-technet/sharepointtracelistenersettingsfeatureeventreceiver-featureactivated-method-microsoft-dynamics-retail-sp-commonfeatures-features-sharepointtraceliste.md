---
title: SharePointTraceListenerSettingsFeatureEventReceiver.FeatureActivated Method  (Microsoft.Dynamics.Retail.SP.CommonFeatures.Features.SharePointTraceListenerSettingsFeature)
TOCTitle: FeatureActivated Method
ms:assetid: M:Microsoft.Dynamics.Retail.SP.CommonFeatures.Features.SharePointTraceListenerSettingsFeature.SharePointTraceListenerSettingsFeatureEventReceiver.FeatureActivated(Microsoft.SharePoint.SPFeatureReceiverProperties)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sp.commonfeatures.features.sharepointtracelistenersettingsfeature.sharepointtracelistenersettingsfeatureeventreceiver.featureactivated(v=AX.60)
ms:contentKeyID: 62205839
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SP.CommonFeatures.Features.SharePointTraceListenerSettingsFeature.SharePointTraceListenerSettingsFeatureEventReceiver.FeatureActivated
dev_langs:
- CSharp
- C++
- VB
---

# FeatureActivated Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Handles the event that is raised after a Feature is activated.

**Namespace:**  [Microsoft.Dynamics.Retail.SP.CommonFeatures.Features.SharePointTraceListenerSettingsFeature](microsoft-dynamics-retail-sp-commonfeatures-features-sharepointtracelistenersettingsfeature-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Storefront (in Microsoft.Dynamics.Retail.SP.Web.Storefront.dll)

## Syntax

``` vb
'Declaration
Public Overrides Sub FeatureActivated ( _
    properties As SPFeatureReceiverProperties _
)
'Usage
Dim instance As SharePointTraceListenerSettingsFeatureEventReceiver
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

[SharePointTraceListenerSettingsFeatureEventReceiver Class](sharepointtracelistenersettingsfeatureeventreceiver-class-microsoft-dynamics-retail-sp-commonfeatures-features-sharepointtracelistenersettingsfeature.md)

[Microsoft.Dynamics.Retail.SP.CommonFeatures.Features.SharePointTraceListenerSettingsFeature Namespace](microsoft-dynamics-retail-sp-commonfeatures-features-sharepointtracelistenersettingsfeature-namespace.md)

