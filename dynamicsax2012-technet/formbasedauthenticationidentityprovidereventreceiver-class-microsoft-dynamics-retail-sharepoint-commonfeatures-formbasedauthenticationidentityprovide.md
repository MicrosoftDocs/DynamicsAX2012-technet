---
title: FormBasedAuthenticationIdentityProviderEventReceiver Class (Microsoft.Dynamics.Retail.SharePoint.CommonFeatures.FormBasedAuthenticationIdentityProvider)
TOCTitle: FormBasedAuthenticationIdentityProviderEventReceiver Class
ms:assetid: T:Microsoft.Dynamics.Retail.SharePoint.CommonFeatures.FormBasedAuthenticationIdentityProvider.FormBasedAuthenticationIdentityProviderEventReceiver
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.commonfeatures.formbasedauthenticationidentityprovider.formbasedauthenticationidentityprovidereventreceiver(v=AX.60)
ms:contentKeyID: 62203648
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.CommonFeatures.FormBasedAuthenticationIdentityProvider.FormBasedAuthenticationIdentityProviderEventReceiver
dev_langs:
- CSharp
- C++
- VB
---

# FormBasedAuthenticationIdentityProviderEventReceiver Class

This class handles events raised during feature activation, deactivation, installation, uninstallation, and upgrade.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.CommonFeatures.FormBasedAuthenticationIdentityProvider](microsoft-dynamics-retail-sharepoint-commonfeatures-formbasedauthenticationidentityprovider-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Storefront (in Microsoft.Dynamics.Retail.SP.Web.Storefront.dll)

## Syntax

``` vb
'Declaration
<GuidAttribute("6e5389e9-ba8d-44f6-8b55-00ab82b714ca")> _
Public Class FormBasedAuthenticationIdentityProviderEventReceiver _
    Inherits SPFeatureReceiver
'Usage
Dim instance As FormBasedAuthenticationIdentityProviderEventReceiver
```

``` csharp
[GuidAttribute("6e5389e9-ba8d-44f6-8b55-00ab82b714ca")]
public class FormBasedAuthenticationIdentityProviderEventReceiver : SPFeatureReceiver
```

``` c++
[GuidAttribute(L"6e5389e9-ba8d-44f6-8b55-00ab82b714ca")]
public ref class FormBasedAuthenticationIdentityProviderEventReceiver : public SPFeatureReceiver
```

## Remarks

The GUID attached to this class may be used during packaging and should not be modified.

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  SPFeatureReceiver  
    Microsoft.Dynamics.Retail.SharePoint.CommonFeatures.FormBasedAuthenticationIdentityProvider.FormBasedAuthenticationIdentityProviderEventReceiver  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Retail.SharePoint.CommonFeatures.FormBasedAuthenticationIdentityProvider Namespace](microsoft-dynamics-retail-sharepoint-commonfeatures-formbasedauthenticationidentityprovider-namespace.md)

