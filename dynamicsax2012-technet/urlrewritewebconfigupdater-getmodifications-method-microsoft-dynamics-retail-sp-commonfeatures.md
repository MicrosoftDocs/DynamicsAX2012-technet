---
title: UrlRewriteWebConfigUpdater.GetModifications Method  (Microsoft.Dynamics.Retail.SP.CommonFeatures)
TOCTitle: GetModifications Method
ms:assetid: M:Microsoft.Dynamics.Retail.SP.CommonFeatures.UrlRewriteWebConfigUpdater.GetModifications(Microsoft.SharePoint.SPFeaturePropertyCollection)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sp.commonfeatures.urlrewritewebconfigupdater.getmodifications(v=AX.60)
ms:contentKeyID: 62207670
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SP.CommonFeatures.UrlRewriteWebConfigUpdater.GetModifications
dev_langs:
- CSharp
- C++
- VB
---

# GetModifications Method

This gets the modification that are supposed to be done or undone during activation/deactivation.

**Namespace:**  [Microsoft.Dynamics.Retail.SP.CommonFeatures](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Storefront (in Microsoft.Dynamics.Retail.SP.Web.Storefront.dll)

## Syntax

``` vb
'Declaration
Public Overrides Function GetModifications ( _
    properties As SPFeaturePropertyCollection _
) As SPWebConfigModification()
'Usage
Dim instance As UrlRewriteWebConfigUpdater
Dim properties As SPFeaturePropertyCollection
Dim returnValue As SPWebConfigModification()

returnValue = instance.GetModifications(properties)
```

``` csharp
public override SPWebConfigModification[] GetModifications(
    SPFeaturePropertyCollection properties
)
```

``` c++
public:
virtual array<SPWebConfigModification^>^ GetModifications(
    SPFeaturePropertyCollection^ properties
) override
```

#### Parameters

  - properties  
    Type: SPFeaturePropertyCollection  

#### Return Value

Type: SPWebConfigModification\[\]  
Returns SPWebConfigModification.  

## See Also

#### Reference

[UrlRewriteWebConfigUpdater Class](urlrewritewebconfigupdater-class-microsoft-dynamics-retail-sp-commonfeatures.md)

[Microsoft.Dynamics.Retail.SP.CommonFeatures Namespace](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)

