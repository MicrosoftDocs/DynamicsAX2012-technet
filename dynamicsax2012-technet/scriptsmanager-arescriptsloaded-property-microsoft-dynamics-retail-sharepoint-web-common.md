---
title: ScriptsManager.AreScriptsLoaded Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Common)
TOCTitle: AreScriptsLoaded Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Common.ScriptsManager.AreScriptsLoaded
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.common.scriptsmanager.arescriptsloaded(v=AX.60)
ms:contentKeyID: 62206130
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Common.ScriptsManager.AreScriptsLoaded
dev_langs:
- CSharp
- C++
- VB
---

# AreScriptsLoaded Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets whether if scripts have already been loaded for the current page lifecycle.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Common](microsoft-dynamics-retail-sharepoint-web-common-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Shared Property AreScriptsLoaded As Boolean
    Get
    Set
'Usage
Dim value As Boolean

value = ScriptsManager.AreScriptsLoaded

ScriptsManager.AreScriptsLoaded = value
```

``` csharp
public static bool AreScriptsLoaded { get; set; }
```

``` c++
public:
static property bool AreScriptsLoaded {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[ScriptsManager Class](scriptsmanager-class-microsoft-dynamics-retail-sharepoint-web-common.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Common Namespace](microsoft-dynamics-retail-sharepoint-web-common-namespace.md)

