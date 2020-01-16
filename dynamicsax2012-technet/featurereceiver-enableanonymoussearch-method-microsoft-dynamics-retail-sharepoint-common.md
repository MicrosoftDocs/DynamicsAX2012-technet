---
title: FeatureReceiver.EnableAnonymousSearch Method  (Microsoft.Dynamics.Retail.SharePoint.Common)
TOCTitle: EnableAnonymousSearch Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Common.FeatureReceiver.EnableAnonymousSearch(Microsoft.SharePoint.SPSite,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.common.featurereceiver.enableanonymoussearch(v=AX.60)
ms:contentKeyID: 62206810
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Common.FeatureReceiver.EnableAnonymousSearch
dev_langs:
- CSharp
- C++
- VB
---

# EnableAnonymousSearch Method

Enables search for anonymous users

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Common](microsoft-dynamics-retail-sharepoint-common-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Shared Sub EnableAnonymousSearch ( _
    site As SPSite, _
    queryParameterTemplateContent As String _
)
'Usage
Dim site As SPSite
Dim queryParameterTemplateContent As String

FeatureReceiver.EnableAnonymousSearch(site, _
    queryParameterTemplateContent)
```

``` csharp
public static void EnableAnonymousSearch(
    SPSite site,
    string queryParameterTemplateContent
)
```

``` c++
public:
static void EnableAnonymousSearch(
    SPSite^ site, 
    String^ queryParameterTemplateContent
)
```

#### Parameters

  - site  
    Type: SPSite  

<!-- end list -->

  - queryParameterTemplateContent  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[FeatureReceiver Class](featurereceiver-class-microsoft-dynamics-retail-sharepoint-common.md)

[Microsoft.Dynamics.Retail.SharePoint.Common Namespace](microsoft-dynamics-retail-sharepoint-common-namespace.md)

