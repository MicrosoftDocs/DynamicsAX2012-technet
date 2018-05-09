---
title: FormBasedAuthenticationIdentityProviderEventReceiver.FeatureActivated Method  (Microsoft.Dynamics.Retail.SharePoint.CommonFeatures.FormBasedAuthenticationIdentityProvider)
TOCTitle: FeatureActivated Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.CommonFeatures.FormBasedAuthenticationIdentityProvider.FormBasedAuthenticationIdentityProviderEventReceiver.FeatureActivated(Microsoft.SharePoint.SPFeatureReceiverProperties)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.commonfeatures.formbasedauthenticationidentityprovider.formbasedauthenticationidentityprovidereventreceiver.featureactivated(v=AX.60)
ms:contentKeyID: 62201960
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.CommonFeatures.FormBasedAuthenticationIdentityProvider.FormBasedAuthenticationIdentityProviderEventReceiver.FeatureActivated
dev_langs:
- CSharp
- C++
- VB
---

# FeatureActivated Method

Handles the event that is raised after a Feature is activated.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.CommonFeatures.FormBasedAuthenticationIdentityProvider](microsoft-dynamics-retail-sharepoint-commonfeatures-formbasedauthenticationidentityprovider-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Storefront (in Microsoft.Dynamics.Retail.SP.Web.Storefront.dll)

## Syntax

``` vb
'Declaration
Public Overrides Sub FeatureActivated ( _
    properties As SPFeatureReceiverProperties _
)
'Usage
Dim instance As FormBasedAuthenticationIdentityProviderEventReceiver
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

[FormBasedAuthenticationIdentityProviderEventReceiver Class](formbasedauthenticationidentityprovidereventreceiver-class-microsoft-dynamics-retail-sharepoint-commonfeatures-formbasedauthenticationidentityprovide.md)

[Microsoft.Dynamics.Retail.SharePoint.CommonFeatures.FormBasedAuthenticationIdentityProvider Namespace](microsoft-dynamics-retail-sharepoint-commonfeatures-formbasedauthenticationidentityprovider-namespace.md)

