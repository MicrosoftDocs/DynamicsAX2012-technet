---
title: WebConfigUpdater.GetModifications Method  (Microsoft.Dynamics.Retail.SharePoint.CommonFeatures)
TOCTitle: GetModifications Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.CommonFeatures.WebConfigUpdater.GetModifications(Microsoft.SharePoint.SPFeaturePropertyCollection)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.commonfeatures.webconfigupdater.getmodifications(v=AX.60)
ms:contentKeyID: 62207305
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.CommonFeatures.WebConfigUpdater.GetModifications
dev_langs:
- CSharp
- C++
- VB
---

# GetModifications Method

This gets the modification that are supposed to be done or undone during activation/deactivation.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.CommonFeatures](microsoft-dynamics-retail-sharepoint-commonfeatures-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Storefront (in Microsoft.Dynamics.Retail.SP.Web.Storefront.dll)

## Syntax

``` vb
'Declaration
Public MustOverride Function GetModifications ( _
    properties As SPFeaturePropertyCollection _
) As SPWebConfigModification()
'Usage
Dim instance As WebConfigUpdater
Dim properties As SPFeaturePropertyCollection
Dim returnValue As SPWebConfigModification()

returnValue = instance.GetModifications(properties)
```

``` csharp
public abstract SPWebConfigModification[] GetModifications(
    SPFeaturePropertyCollection properties
)
```

``` c++
public:
virtual array<SPWebConfigModification^>^ GetModifications(
    SPFeaturePropertyCollection^ properties
) abstract
```

#### Parameters

  - properties  
    Type: SPFeaturePropertyCollection  

#### Return Value

Type: SPWebConfigModification\[\]  
Returns SPWebConfigModification.  

## See Also

#### Reference

[WebConfigUpdater Class](webconfigupdater-class-microsoft-dynamics-retail-sharepoint-commonfeatures.md)

[Microsoft.Dynamics.Retail.SharePoint.CommonFeatures Namespace](microsoft-dynamics-retail-sharepoint-commonfeatures-namespace.md)

