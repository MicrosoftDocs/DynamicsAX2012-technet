---
title: TrustedIdentityProviderSettingsFeatureEventReceiver Class (Microsoft.Dynamics.Retail.SP.CommonFeatures.Features.TrustedIdentityProviderSettingsFeature)
TOCTitle: TrustedIdentityProviderSettingsFeatureEventReceiver Class
ms:assetid: T:Microsoft.Dynamics.Retail.SP.CommonFeatures.Features.TrustedIdentityProviderSettingsFeature.TrustedIdentityProviderSettingsFeatureEventReceiver
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sp.commonfeatures.features.trustedidentityprovidersettingsfeature.trustedidentityprovidersettingsfeatureeventreceiver(v=AX.60)
ms:contentKeyID: 62204295
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SP.CommonFeatures.Features.TrustedIdentityProviderSettingsFeature.TrustedIdentityProviderSettingsFeatureEventReceiver
dev_langs:
- CSharp
- C++
- VB
---

# TrustedIdentityProviderSettingsFeatureEventReceiver Class

This class handles events raised during feature activation, deactivation, installation, uninstallation, and upgrade.

**Namespace:**  [Microsoft.Dynamics.Retail.SP.CommonFeatures.Features.TrustedIdentityProviderSettingsFeature](microsoft-dynamics-retail-sp-commonfeatures-features-trustedidentityprovidersettingsfeature-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Storefront (in Microsoft.Dynamics.Retail.SP.Web.Storefront.dll)

## Syntax

``` vb
'Declaration
<GuidAttribute("effb5a84-c5dd-4cab-a1c4-2f8482e98d9c")> _
Public Class TrustedIdentityProviderSettingsFeatureEventReceiver _
    Inherits SPFeatureReceiver
'Usage
Dim instance As TrustedIdentityProviderSettingsFeatureEventReceiver
```

``` csharp
[GuidAttribute("effb5a84-c5dd-4cab-a1c4-2f8482e98d9c")]
public class TrustedIdentityProviderSettingsFeatureEventReceiver : SPFeatureReceiver
```

``` c++
[GuidAttribute(L"effb5a84-c5dd-4cab-a1c4-2f8482e98d9c")]
public ref class TrustedIdentityProviderSettingsFeatureEventReceiver : public SPFeatureReceiver
```

## Remarks

The GUID attached to this class may be used during packaging and should not be modified.

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  SPFeatureReceiver  
    Microsoft.Dynamics.Retail.SP.CommonFeatures.Features.TrustedIdentityProviderSettingsFeature.TrustedIdentityProviderSettingsFeatureEventReceiver  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Retail.SP.CommonFeatures.Features.TrustedIdentityProviderSettingsFeature Namespace](microsoft-dynamics-retail-sp-commonfeatures-features-trustedidentityprovidersettingsfeature-namespace.md)

