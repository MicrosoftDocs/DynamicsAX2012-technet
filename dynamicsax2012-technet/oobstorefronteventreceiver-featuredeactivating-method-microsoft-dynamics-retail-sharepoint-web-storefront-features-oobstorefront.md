---
title: OOBStorefrontEventReceiver.FeatureDeactivating Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Storefront.Features.OOBStorefront)
TOCTitle: FeatureDeactivating Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Storefront.Features.OOBStorefront.OOBStorefrontEventReceiver.FeatureDeactivating(Microsoft.SharePoint.SPFeatureReceiverProperties)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.storefront.features.oobstorefront.oobstorefronteventreceiver.featuredeactivating(v=AX.60)
ms:contentKeyID: 62205804
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Storefront.Features.OOBStorefront.OOBStorefrontEventReceiver.FeatureDeactivating
dev_langs:
- CSharp
- C++
- VB
---

# FeatureDeactivating Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Called when OOb Storefront feature is being deactivated.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Storefront.Features.OOBStorefront](microsoft-dynamics-retail-sharepoint-web-storefront-features-oobstorefront-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Storefront (in Microsoft.Dynamics.Retail.SP.Web.Storefront.dll)

## Syntax

``` vb
'Declaration
Public Overrides Sub FeatureDeactivating ( _
    properties As SPFeatureReceiverProperties _
)
'Usage
Dim instance As OOBStorefrontEventReceiver
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

[OOBStorefrontEventReceiver Class](oobstorefronteventreceiver-class-microsoft-dynamics-retail-sharepoint-web-storefront-features-oobstorefront.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Storefront.Features.OOBStorefront Namespace](microsoft-dynamics-retail-sharepoint-web-storefront-features-oobstorefront-namespace.md)

