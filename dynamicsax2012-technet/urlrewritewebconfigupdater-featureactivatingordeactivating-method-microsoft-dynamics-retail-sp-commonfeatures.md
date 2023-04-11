---
title: UrlRewriteWebConfigUpdater.FeatureActivatingOrDeactivating Method  (Microsoft.Dynamics.Retail.SP.CommonFeatures)
TOCTitle: FeatureActivatingOrDeactivating Method
ms:assetid: M:Microsoft.Dynamics.Retail.SP.CommonFeatures.UrlRewriteWebConfigUpdater.FeatureActivatingOrDeactivating(Microsoft.SharePoint.SPFeatureReceiverProperties,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sp.commonfeatures.urlrewritewebconfigupdater.featureactivatingordeactivating(v=AX.60)
ms:contentKeyID: 62205848
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SP.CommonFeatures.UrlRewriteWebConfigUpdater.FeatureActivatingOrDeactivating
dev_langs:
- CSharp
- C++
- VB
---

# FeatureActivatingOrDeactivating Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Main implementation of activation and deactivation.

**Namespace:**  [Microsoft.Dynamics.Retail.SP.CommonFeatures](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Storefront (in Microsoft.Dynamics.Retail.SP.Web.Storefront.dll)

## Syntax

``` vb
'Declaration
Public Overrides Sub FeatureActivatingOrDeactivating ( _
    properties As SPFeatureReceiverProperties, _
    isActivation As Boolean _
)
'Usage
Dim instance As UrlRewriteWebConfigUpdater
Dim properties As SPFeatureReceiverProperties
Dim isActivation As Boolean

instance.FeatureActivatingOrDeactivating(properties, _
    isActivation)
```

``` csharp
public override void FeatureActivatingOrDeactivating(
    SPFeatureReceiverProperties properties,
    bool isActivation
)
```

``` c++
public:
virtual void FeatureActivatingOrDeactivating(
    SPFeatureReceiverProperties^ properties, 
    bool isActivation
) override
```

#### Parameters

  - properties  
    Type: SPFeatureReceiverProperties  

<!-- end list -->

  - isActivation  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[UrlRewriteWebConfigUpdater Class](urlrewritewebconfigupdater-class-microsoft-dynamics-retail-sp-commonfeatures.md)

[Microsoft.Dynamics.Retail.SP.CommonFeatures Namespace](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)

