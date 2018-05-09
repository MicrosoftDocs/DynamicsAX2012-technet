---
title: MiscSettingsFeatureEventReceiver Class (Microsoft.Dynamics.Retail.SP.CommonFeatures.Features.MiscSettingsFeature)
TOCTitle: MiscSettingsFeatureEventReceiver Class
ms:assetid: T:Microsoft.Dynamics.Retail.SP.CommonFeatures.Features.MiscSettingsFeature.MiscSettingsFeatureEventReceiver
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sp.commonfeatures.features.miscsettingsfeature.miscsettingsfeatureeventreceiver(v=AX.60)
ms:contentKeyID: 62206068
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SP.CommonFeatures.Features.MiscSettingsFeature.MiscSettingsFeatureEventReceiver
dev_langs:
- CSharp
- C++
- VB
---

# MiscSettingsFeatureEventReceiver Class

This class handles events raised during feature activation, deactivation, installation, uninstallation, and upgrade.

**Namespace:**  [Microsoft.Dynamics.Retail.SP.CommonFeatures.Features.MiscSettingsFeature](microsoft-dynamics-retail-sp-commonfeatures-features-miscsettingsfeature-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Storefront (in Microsoft.Dynamics.Retail.SP.Web.Storefront.dll)

## Syntax

``` vb
'Declaration
<GuidAttribute("ce53edf2-a933-4d46-993f-55675e3b804c")> _
Public Class MiscSettingsFeatureEventReceiver _
    Inherits SPFeatureReceiver
'Usage
Dim instance As MiscSettingsFeatureEventReceiver
```

``` csharp
[GuidAttribute("ce53edf2-a933-4d46-993f-55675e3b804c")]
public class MiscSettingsFeatureEventReceiver : SPFeatureReceiver
```

``` c++
[GuidAttribute(L"ce53edf2-a933-4d46-993f-55675e3b804c")]
public ref class MiscSettingsFeatureEventReceiver : public SPFeatureReceiver
```

## Remarks

The GUID attached to this class may be used during packaging and should not be modified.

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))  
  SPFeatureReceiver  
    Microsoft.Dynamics.Retail.SP.CommonFeatures.Features.MiscSettingsFeature.MiscSettingsFeatureEventReceiver  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Retail.SP.CommonFeatures.Features.MiscSettingsFeature Namespace](microsoft-dynamics-retail-sp-commonfeatures-features-miscsettingsfeature-namespace.md)

