---
title: CustomClaimsProviderSettingsFeatureEventReceiver Class (Microsoft.Dynamics.Retail.SharePoint.CommonFeatures.CustomClaimsProviderSettingsFeature)
TOCTitle: CustomClaimsProviderSettingsFeatureEventReceiver Class
ms:assetid: T:Microsoft.Dynamics.Retail.SharePoint.CommonFeatures.CustomClaimsProviderSettingsFeature.CustomClaimsProviderSettingsFeatureEventReceiver
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.commonfeatures.customclaimsprovidersettingsfeature.customclaimsprovidersettingsfeatureeventreceiver(v=AX.60)
ms:contentKeyID: 62202598
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.CommonFeatures.CustomClaimsProviderSettingsFeature.CustomClaimsProviderSettingsFeatureEventReceiver
dev_langs:
- CSharp
- C++
- VB
---

# CustomClaimsProviderSettingsFeatureEventReceiver Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

This class handles events raised during feature activation, deactivation, installation, uninstallation, and upgrade.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.CommonFeatures.CustomClaimsProviderSettingsFeature](microsoft-dynamics-retail-sharepoint-commonfeatures-customclaimsprovidersettingsfeature-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Storefront (in Microsoft.Dynamics.Retail.SP.Web.Storefront.dll)

## Syntax

``` vb
'Declaration
<GuidAttribute("b7feb4bd-2767-40d7-9fba-6fd269bf014d")> _
Public Class CustomClaimsProviderSettingsFeatureEventReceiver _
    Inherits SPFeatureReceiver
'Usage
Dim instance As CustomClaimsProviderSettingsFeatureEventReceiver
```

``` csharp
[GuidAttribute("b7feb4bd-2767-40d7-9fba-6fd269bf014d")]
public class CustomClaimsProviderSettingsFeatureEventReceiver : SPFeatureReceiver
```

``` c++
[GuidAttribute(L"b7feb4bd-2767-40d7-9fba-6fd269bf014d")]
public ref class CustomClaimsProviderSettingsFeatureEventReceiver : public SPFeatureReceiver
```

## Remarks

The GUID attached to this class may be used during packaging and should not be modified.

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  SPFeatureReceiver  
    Microsoft.Dynamics.Retail.SharePoint.CommonFeatures.CustomClaimsProviderSettingsFeature.CustomClaimsProviderSettingsFeatureEventReceiver  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Retail.SharePoint.CommonFeatures.CustomClaimsProviderSettingsFeature Namespace](microsoft-dynamics-retail-sharepoint-commonfeatures-customclaimsprovidersettingsfeature-namespace.md)

