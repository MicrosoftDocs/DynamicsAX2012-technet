---
title: LoggingServiceFeatureEventReceiver.FeatureDeactivating Method  (Microsoft.Dynamics.Retail.SP.CommonFeatures.Features.LoggingServiceFeature)
TOCTitle: FeatureDeactivating Method
ms:assetid: M:Microsoft.Dynamics.Retail.SP.CommonFeatures.Features.LoggingServiceFeature.LoggingServiceFeatureEventReceiver.FeatureDeactivating(Microsoft.SharePoint.SPFeatureReceiverProperties)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sp.commonfeatures.features.loggingservicefeature.loggingservicefeatureeventreceiver.featuredeactivating(v=AX.60)
ms:contentKeyID: 62203816
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SP.CommonFeatures.Features.LoggingServiceFeature.LoggingServiceFeatureEventReceiver.FeatureDeactivating
dev_langs:
- CSharp
- C++
- VB
---

# FeatureDeactivating Method

Handles the event that is raised when a Feature is deactivated.

**Namespace:**  [Microsoft.Dynamics.Retail.SP.CommonFeatures.Features.LoggingServiceFeature](microsoft-dynamics-retail-sp-commonfeatures-features-loggingservicefeature-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Storefront (in Microsoft.Dynamics.Retail.SP.Web.Storefront.dll)

## Syntax

``` vb
'Declaration
Public Overrides Sub FeatureDeactivating ( _
    properties As SPFeatureReceiverProperties _
)
'Usage
Dim instance As LoggingServiceFeatureEventReceiver
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

[LoggingServiceFeatureEventReceiver Class](loggingservicefeatureeventreceiver-class-microsoft-dynamics-retail-sp-commonfeatures-features-loggingservicefeature.md)

[Microsoft.Dynamics.Retail.SP.CommonFeatures.Features.LoggingServiceFeature Namespace](microsoft-dynamics-retail-sp-commonfeatures-features-loggingservicefeature-namespace.md)

