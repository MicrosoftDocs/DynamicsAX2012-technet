---
title: OOBStorefrontEventReceiver Class (Microsoft.Dynamics.Retail.SharePoint.Web.Storefront.Features.OOBStorefront)
TOCTitle: OOBStorefrontEventReceiver Class
ms:assetid: T:Microsoft.Dynamics.Retail.SharePoint.Web.Storefront.Features.OOBStorefront.OOBStorefrontEventReceiver
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.web.storefront.features.oobstorefront.oobstorefronteventreceiver(v=AX.60)
ms:contentKeyID: 62204197
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Storefront.Features.OOBStorefront.OOBStorefrontEventReceiver
dev_langs:
- CSharp
- C++
- VB
---

# OOBStorefrontEventReceiver Class

This class handles events raised during feature activation, deactivation, installation, uninstallation, and upgrade.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Storefront.Features.OOBStorefront](microsoft-dynamics-retail-sharepoint-web-storefront-features-oobstorefront-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Storefront (in Microsoft.Dynamics.Retail.SP.Web.Storefront.dll)

## Syntax

``` vb
'Declaration
<GuidAttribute("62ac3959-52bc-4f9b-aa23-84656aff7213")> _
Public Class OOBStorefrontEventReceiver _
    Inherits SPFeatureReceiver
'Usage
Dim instance As OOBStorefrontEventReceiver
```

``` csharp
[GuidAttribute("62ac3959-52bc-4f9b-aa23-84656aff7213")]
public class OOBStorefrontEventReceiver : SPFeatureReceiver
```

``` c++
[GuidAttribute(L"62ac3959-52bc-4f9b-aa23-84656aff7213")]
public ref class OOBStorefrontEventReceiver : public SPFeatureReceiver
```

## Remarks

The GUID attached to this class may be used during packaging and should not be modified.

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))  
  SPFeatureReceiver  
    Microsoft.Dynamics.Retail.SharePoint.Web.Storefront.Features.OOBStorefront.OOBStorefrontEventReceiver  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Retail.SharePoint.Web.Storefront.Features.OOBStorefront Namespace](microsoft-dynamics-retail-sharepoint-web-storefront-features-oobstorefront-namespace.md)

