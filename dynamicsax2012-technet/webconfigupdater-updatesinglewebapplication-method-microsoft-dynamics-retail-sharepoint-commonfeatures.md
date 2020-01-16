---
title: WebConfigUpdater.UpdateSingleWebApplication Method  (Microsoft.Dynamics.Retail.SharePoint.CommonFeatures)
TOCTitle: UpdateSingleWebApplication Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.CommonFeatures.WebConfigUpdater.UpdateSingleWebApplication(Microsoft.SharePoint.Administration.SPWebApplication,Microsoft.SharePoint.SPFeaturePropertyCollection,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.commonfeatures.webconfigupdater.updatesinglewebapplication(v=AX.60)
ms:contentKeyID: 62206348
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.CommonFeatures.WebConfigUpdater.UpdateSingleWebApplication
dev_langs:
- CSharp
- C++
- VB
---

# UpdateSingleWebApplication Method

This updates a single web application with the config changes (during activation and deactivation).

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.CommonFeatures](microsoft-dynamics-retail-sharepoint-commonfeatures-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Storefront (in Microsoft.Dynamics.Retail.SP.Web.Storefront.dll)

## Syntax

``` vb
'Declaration
Public Sub UpdateSingleWebApplication ( _
    webApp As SPWebApplication, _
    properties As SPFeaturePropertyCollection, _
    isAdd As Boolean _
)
'Usage
Dim instance As WebConfigUpdater
Dim webApp As SPWebApplication
Dim properties As SPFeaturePropertyCollection
Dim isAdd As Boolean

instance.UpdateSingleWebApplication(webApp, _
    properties, isAdd)
```

``` csharp
public void UpdateSingleWebApplication(
    SPWebApplication webApp,
    SPFeaturePropertyCollection properties,
    bool isAdd
)
```

``` c++
public:
void UpdateSingleWebApplication(
    SPWebApplication^ webApp, 
    SPFeaturePropertyCollection^ properties, 
    bool isAdd
)
```

#### Parameters

  - webApp  
    Type: SPWebApplication  

<!-- end list -->

  - properties  
    Type: SPFeaturePropertyCollection  

<!-- end list -->

  - isAdd  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[WebConfigUpdater Class](webconfigupdater-class-microsoft-dynamics-retail-sharepoint-commonfeatures.md)

[Microsoft.Dynamics.Retail.SharePoint.CommonFeatures Namespace](microsoft-dynamics-retail-sharepoint-commonfeatures-namespace.md)

