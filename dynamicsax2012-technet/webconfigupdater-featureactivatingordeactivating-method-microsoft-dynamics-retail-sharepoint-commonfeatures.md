---
title: WebConfigUpdater.FeatureActivatingOrDeactivating Method  (Microsoft.Dynamics.Retail.SharePoint.CommonFeatures)
TOCTitle: FeatureActivatingOrDeactivating Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.CommonFeatures.WebConfigUpdater.FeatureActivatingOrDeactivating(Microsoft.SharePoint.SPFeatureReceiverProperties,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.commonfeatures.webconfigupdater.featureactivatingordeactivating(v=AX.60)
ms:contentKeyID: 62206211
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.CommonFeatures.WebConfigUpdater.FeatureActivatingOrDeactivating
dev_langs:
- CSharp
- C++
- VB
---

# FeatureActivatingOrDeactivating Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

This is main implementation of the activation/deactivation functionality.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.CommonFeatures](microsoft-dynamics-retail-sharepoint-commonfeatures-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Storefront (in Microsoft.Dynamics.Retail.SP.Web.Storefront.dll)

## Syntax

``` vb
'Declaration
Public MustOverride Sub FeatureActivatingOrDeactivating ( _
    properties As SPFeatureReceiverProperties, _
    isActivation As Boolean _
)
'Usage
Dim instance As WebConfigUpdater
Dim properties As SPFeatureReceiverProperties
Dim isActivation As Boolean

instance.FeatureActivatingOrDeactivating(properties, _
    isActivation)
```

``` csharp
public abstract void FeatureActivatingOrDeactivating(
    SPFeatureReceiverProperties properties,
    bool isActivation
)
```

``` c++
public:
virtual void FeatureActivatingOrDeactivating(
    SPFeatureReceiverProperties^ properties, 
    bool isActivation
) abstract
```

#### Parameters

  - properties  
    Type: SPFeatureReceiverProperties  

<!-- end list -->

  - isActivation  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[WebConfigUpdater Class](webconfigupdater-class-microsoft-dynamics-retail-sharepoint-commonfeatures.md)

[Microsoft.Dynamics.Retail.SharePoint.CommonFeatures Namespace](microsoft-dynamics-retail-sharepoint-commonfeatures-namespace.md)

