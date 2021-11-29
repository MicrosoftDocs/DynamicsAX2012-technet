---
title: DebugSettingsFeatureEventReceiver Class (Microsoft.Dynamics.Retail.SharePoint.CommonFeatures.DebugSettingsFeature)
TOCTitle: DebugSettingsFeatureEventReceiver Class
ms:assetid: T:Microsoft.Dynamics.Retail.SharePoint.CommonFeatures.DebugSettingsFeature.DebugSettingsFeatureEventReceiver
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.commonfeatures.debugsettingsfeature.debugsettingsfeatureeventreceiver(v=AX.60)
ms:contentKeyID: 62207524
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.CommonFeatures.DebugSettingsFeature.DebugSettingsFeatureEventReceiver
dev_langs:
- CSharp
- C++
- VB
---

# DebugSettingsFeatureEventReceiver Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

This feature class provides functionality to make changes to web.config files in order to turn on debug output.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.CommonFeatures.DebugSettingsFeature](microsoft-dynamics-retail-sharepoint-commonfeatures-debugsettingsfeature-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Storefront (in Microsoft.Dynamics.Retail.SP.Web.Storefront.dll)

## Syntax

``` vb
'Declaration
<GuidAttribute("a3c864ee-cfc9-4ba1-9ec0-0f1b685caf1f")> _
Public Class DebugSettingsFeatureEventReceiver _
    Inherits SPFeatureReceiver
'Usage
Dim instance As DebugSettingsFeatureEventReceiver
```

``` csharp
[GuidAttribute("a3c864ee-cfc9-4ba1-9ec0-0f1b685caf1f")]
public class DebugSettingsFeatureEventReceiver : SPFeatureReceiver
```

``` c++
[GuidAttribute(L"a3c864ee-cfc9-4ba1-9ec0-0f1b685caf1f")]
public ref class DebugSettingsFeatureEventReceiver : public SPFeatureReceiver
```

## Remarks

The GUID attached to this class may be used during packaging and should not be modified.

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  SPFeatureReceiver  
    Microsoft.Dynamics.Retail.SharePoint.CommonFeatures.DebugSettingsFeature.DebugSettingsFeatureEventReceiver  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Retail.SharePoint.CommonFeatures.DebugSettingsFeature Namespace](microsoft-dynamics-retail-sharepoint-commonfeatures-debugsettingsfeature-namespace.md)

