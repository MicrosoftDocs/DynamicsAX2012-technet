---
title: WebConfigUpdater.GetEnsureAppSettingsSectionModification Method  (Microsoft.Dynamics.Retail.SharePoint.CommonFeatures)
TOCTitle: GetEnsureAppSettingsSectionModification Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.CommonFeatures.WebConfigUpdater.GetEnsureAppSettingsSectionModification
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.commonfeatures.webconfigupdater.getensureappsettingssectionmodification(v=AX.60)
ms:contentKeyID: 62204891
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.CommonFeatures.WebConfigUpdater.GetEnsureAppSettingsSectionModification
dev_langs:
- CSharp
- C++
- VB
---

# GetEnsureAppSettingsSectionModification Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the ensure app settings section modification.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.CommonFeatures](microsoft-dynamics-retail-sharepoint-commonfeatures-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Storefront (in Microsoft.Dynamics.Retail.SP.Web.Storefront.dll)

## Syntax

``` vb
'Declaration
Protected Function GetEnsureAppSettingsSectionModification As SPWebConfigModification
'Usage
Dim returnValue As SPWebConfigModification

returnValue = Me.GetEnsureAppSettingsSectionModification()
```

``` csharp
protected SPWebConfigModification GetEnsureAppSettingsSectionModification()
```

``` c++
protected:
SPWebConfigModification^ GetEnsureAppSettingsSectionModification()
```

#### Return Value

Type: SPWebConfigModification  
A WebConfigModification object that ensures that app settings section exists.  

## See Also

#### Reference

[WebConfigUpdater Class](webconfigupdater-class-microsoft-dynamics-retail-sharepoint-commonfeatures.md)

[Microsoft.Dynamics.Retail.SharePoint.CommonFeatures Namespace](microsoft-dynamics-retail-sharepoint-commonfeatures-namespace.md)

