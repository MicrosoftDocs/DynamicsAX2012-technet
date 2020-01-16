---
title: LoggingServiceFeatureEventReceiver Class (Microsoft.Dynamics.Retail.SP.CommonFeatures.Features.LoggingServiceFeature)
TOCTitle: LoggingServiceFeatureEventReceiver Class
ms:assetid: T:Microsoft.Dynamics.Retail.SP.CommonFeatures.Features.LoggingServiceFeature.LoggingServiceFeatureEventReceiver
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sp.commonfeatures.features.loggingservicefeature.loggingservicefeatureeventreceiver(v=AX.60)
ms:contentKeyID: 62207348
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SP.CommonFeatures.Features.LoggingServiceFeature.LoggingServiceFeatureEventReceiver
dev_langs:
- CSharp
- C++
- VB
---

# LoggingServiceFeatureEventReceiver Class

This class handles events raised during feature activation, deactivation, installation, uninstallation, and upgrade.

**Namespace:**  [Microsoft.Dynamics.Retail.SP.CommonFeatures.Features.LoggingServiceFeature](microsoft-dynamics-retail-sp-commonfeatures-features-loggingservicefeature-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Storefront (in Microsoft.Dynamics.Retail.SP.Web.Storefront.dll)

## Syntax

``` vb
'Declaration
<GuidAttribute("5104e645-b3f5-4e3b-91ca-116c0cdb5712")> _
Public Class LoggingServiceFeatureEventReceiver _
    Inherits SPFeatureReceiver
'Usage
Dim instance As LoggingServiceFeatureEventReceiver
```

``` csharp
[GuidAttribute("5104e645-b3f5-4e3b-91ca-116c0cdb5712")]
public class LoggingServiceFeatureEventReceiver : SPFeatureReceiver
```

``` c++
[GuidAttribute(L"5104e645-b3f5-4e3b-91ca-116c0cdb5712")]
public ref class LoggingServiceFeatureEventReceiver : public SPFeatureReceiver
```

## Remarks

The GUID attached to this class may be used during packaging and should not be modified.

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  SPFeatureReceiver  
    Microsoft.Dynamics.Retail.SP.CommonFeatures.Features.LoggingServiceFeature.LoggingServiceFeatureEventReceiver  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Retail.SP.CommonFeatures.Features.LoggingServiceFeature Namespace](microsoft-dynamics-retail-sp-commonfeatures-features-loggingservicefeature-namespace.md)

