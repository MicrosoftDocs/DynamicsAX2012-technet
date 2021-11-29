---
title: CommerceRuntimeSettingsFeatureEventReceiver Class (Microsoft.Dynamics.Retail.SP.CommerceRuntime.Features.Settings)
TOCTitle: CommerceRuntimeSettingsFeatureEventReceiver Class
ms:assetid: T:Microsoft.Dynamics.Retail.SP.CommerceRuntime.Features.Settings.CommerceRuntimeSettingsFeatureEventReceiver
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sp.commerceruntime.features.settings.commerceruntimesettingsfeatureeventreceiver(v=AX.60)
ms:contentKeyID: 62202607
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SP.CommerceRuntime.Features.Settings.CommerceRuntimeSettingsFeatureEventReceiver
dev_langs:
- CSharp
- C++
- VB
---

# CommerceRuntimeSettingsFeatureEventReceiver Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

This class handles events raised during feature activation, deactivation, installation, uninstallation, and upgrade.

**Namespace:**  [Microsoft.Dynamics.Retail.SP.CommerceRuntime.Features.Settings](microsoft-dynamics-retail-sp-commerceruntime-features-settings-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Storefront (in Microsoft.Dynamics.Retail.SP.Web.Storefront.dll)

## Syntax

``` vb
'Declaration
<GuidAttribute("79ebca14-3259-4e21-842c-b157e5de6e0d")> _
Public Class CommerceRuntimeSettingsFeatureEventReceiver _
    Inherits SPFeatureReceiver
'Usage
Dim instance As CommerceRuntimeSettingsFeatureEventReceiver
```

``` csharp
[GuidAttribute("79ebca14-3259-4e21-842c-b157e5de6e0d")]
public class CommerceRuntimeSettingsFeatureEventReceiver : SPFeatureReceiver
```

``` c++
[GuidAttribute(L"79ebca14-3259-4e21-842c-b157e5de6e0d")]
public ref class CommerceRuntimeSettingsFeatureEventReceiver : public SPFeatureReceiver
```

## Remarks

The GUID attached to this class may be used during packaging and should not be modified.

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  SPFeatureReceiver  
    Microsoft.Dynamics.Retail.SP.CommerceRuntime.Features.Settings.CommerceRuntimeSettingsFeatureEventReceiver  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Retail.SP.CommerceRuntime.Features.Settings Namespace](microsoft-dynamics-retail-sp-commerceruntime-features-settings-namespace.md)

