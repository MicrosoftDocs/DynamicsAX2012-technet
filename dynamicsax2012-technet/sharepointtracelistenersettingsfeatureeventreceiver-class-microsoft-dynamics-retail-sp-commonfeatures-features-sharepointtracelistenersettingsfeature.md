---
title: SharePointTraceListenerSettingsFeatureEventReceiver Class (Microsoft.Dynamics.Retail.SP.CommonFeatures.Features.SharePointTraceListenerSettingsFeature)
TOCTitle: SharePointTraceListenerSettingsFeatureEventReceiver Class
ms:assetid: T:Microsoft.Dynamics.Retail.SP.CommonFeatures.Features.SharePointTraceListenerSettingsFeature.SharePointTraceListenerSettingsFeatureEventReceiver
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sp.commonfeatures.features.sharepointtracelistenersettingsfeature.sharepointtracelistenersettingsfeatureeventreceiver(v=AX.60)
ms:contentKeyID: 62204614
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SP.CommonFeatures.Features.SharePointTraceListenerSettingsFeature.SharePointTraceListenerSettingsFeatureEventReceiver
dev_langs:
- CSharp
- C++
- VB
---

# SharePointTraceListenerSettingsFeatureEventReceiver Class

This class handles events raised during feature activation, deactivation, installation, uninstallation, and upgrade.

**Namespace:**  [Microsoft.Dynamics.Retail.SP.CommonFeatures.Features.SharePointTraceListenerSettingsFeature](microsoft-dynamics-retail-sp-commonfeatures-features-sharepointtracelistenersettingsfeature-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Storefront (in Microsoft.Dynamics.Retail.SP.Web.Storefront.dll)

## Syntax

``` vb
'Declaration
<GuidAttribute("1dc5a17b-b4cf-4684-8fa2-0b178798f505")> _
Public Class SharePointTraceListenerSettingsFeatureEventReceiver _
    Inherits SPFeatureReceiver
'Usage
Dim instance As SharePointTraceListenerSettingsFeatureEventReceiver
```

``` csharp
[GuidAttribute("1dc5a17b-b4cf-4684-8fa2-0b178798f505")]
public class SharePointTraceListenerSettingsFeatureEventReceiver : SPFeatureReceiver
```

``` c++
[GuidAttribute(L"1dc5a17b-b4cf-4684-8fa2-0b178798f505")]
public ref class SharePointTraceListenerSettingsFeatureEventReceiver : public SPFeatureReceiver
```

## Remarks

The GUID attached to this class may be used during packaging and should not be modified.

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  SPFeatureReceiver  
    Microsoft.Dynamics.Retail.SP.CommonFeatures.Features.SharePointTraceListenerSettingsFeature.SharePointTraceListenerSettingsFeatureEventReceiver  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Retail.SP.CommonFeatures.Features.SharePointTraceListenerSettingsFeature Namespace](microsoft-dynamics-retail-sp-commonfeatures-features-sharepointtracelistenersettingsfeature-namespace.md)

