---
title: CustomClaimsProviderFeatureEventReceiver Class (Microsoft.Dynamics.Retail.SharePoint.Web.CommonGlobalModules.Features.CustomClaimsProviderFeature)
TOCTitle: CustomClaimsProviderFeatureEventReceiver Class
ms:assetid: T:Microsoft.Dynamics.Retail.SharePoint.Web.CommonGlobalModules.Features.CustomClaimsProviderFeature.CustomClaimsProviderFeatureEventReceiver
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.commonglobalmodules.features.customclaimsproviderfeature.customclaimsproviderfeatureeventreceiver(v=AX.60)
ms:contentKeyID: 62203186
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.CommonGlobalModules.Features.CustomClaimsProviderFeature.CustomClaimsProviderFeatureEventReceiver
dev_langs:
- CSharp
- C++
- VB
---

# CustomClaimsProviderFeatureEventReceiver Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

This class handles events raised during feature activation, deactivation, installation, uninstallation, and upgrade.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.CommonGlobalModules.Features.CustomClaimsProviderFeature](microsoft-dynamics-retail-sharepoint-web-commonglobalmodules-features-customclaimsproviderfeature-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.CommonGlobalModules (in Microsoft.Dynamics.Retail.SP.Web.CommonGlobalModules.dll)

## Syntax

``` vb
'Declaration
<GuidAttribute("27326ad2-62b6-4540-9f2f-80b97e04334d")> _
Public Class CustomClaimsProviderFeatureEventReceiver _
    Inherits SPClaimProviderFeatureReceiver
'Usage
Dim instance As CustomClaimsProviderFeatureEventReceiver
```

``` csharp
[GuidAttribute("27326ad2-62b6-4540-9f2f-80b97e04334d")]
public class CustomClaimsProviderFeatureEventReceiver : SPClaimProviderFeatureReceiver
```

``` c++
[GuidAttribute(L"27326ad2-62b6-4540-9f2f-80b97e04334d")]
public ref class CustomClaimsProviderFeatureEventReceiver : public SPClaimProviderFeatureReceiver
```

## Remarks

The GUID attached to this class may be used during packaging and should not be modified.

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  SPFeatureReceiver  
    SPClaimProviderFeatureReceiver  
      Microsoft.Dynamics.Retail.SharePoint.Web.CommonGlobalModules.Features.CustomClaimsProviderFeature.CustomClaimsProviderFeatureEventReceiver  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Retail.SharePoint.Web.CommonGlobalModules.Features.CustomClaimsProviderFeature Namespace](microsoft-dynamics-retail-sharepoint-web-commonglobalmodules-features-customclaimsproviderfeature-namespace.md)

