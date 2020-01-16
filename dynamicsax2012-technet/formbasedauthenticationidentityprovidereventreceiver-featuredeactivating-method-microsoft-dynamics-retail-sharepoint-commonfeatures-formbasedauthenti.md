---
title: FormBasedAuthenticationIdentityProviderEventReceiver.FeatureDeactivating Method  (Microsoft.Dynamics.Retail.SharePoint.CommonFeatures.FormBasedAuthenticationIdentityProvider)
TOCTitle: FeatureDeactivating Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.CommonFeatures.FormBasedAuthenticationIdentityProvider.FormBasedAuthenticationIdentityProviderEventReceiver.FeatureDeactivating(Microsoft.SharePoint.SPFeatureReceiverProperties)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.commonfeatures.formbasedauthenticationidentityprovider.formbasedauthenticationidentityprovidereventreceiver.featuredeactivating(v=AX.60)
ms:contentKeyID: 62206656
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.CommonFeatures.FormBasedAuthenticationIdentityProvider.FormBasedAuthenticationIdentityProviderEventReceiver.FeatureDeactivating
dev_langs:
- CSharp
- C++
- VB
---

# FeatureDeactivating Method

Handles the event that is raised when a Feature is deactivated.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.CommonFeatures.FormBasedAuthenticationIdentityProvider](microsoft-dynamics-retail-sharepoint-commonfeatures-formbasedauthenticationidentityprovider-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Storefront (in Microsoft.Dynamics.Retail.SP.Web.Storefront.dll)

## Syntax

``` vb
'Declaration
Public Overrides Sub FeatureDeactivating ( _
    properties As SPFeatureReceiverProperties _
)
'Usage
Dim instance As FormBasedAuthenticationIdentityProviderEventReceiver
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

[FormBasedAuthenticationIdentityProviderEventReceiver Class](formbasedauthenticationidentityprovidereventreceiver-class-microsoft-dynamics-retail-sharepoint-commonfeatures-formbasedauthenticationidentityprovide.md)

[Microsoft.Dynamics.Retail.SharePoint.CommonFeatures.FormBasedAuthenticationIdentityProvider Namespace](microsoft-dynamics-retail-sharepoint-commonfeatures-formbasedauthenticationidentityprovider-namespace.md)

