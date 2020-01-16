---
title: FeatureReceiver.RemoveResultSource Method  (Microsoft.Dynamics.Retail.SharePoint.Common)
TOCTitle: RemoveResultSource Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Common.FeatureReceiver.RemoveResultSource(Microsoft.SharePoint.SPWeb,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.common.featurereceiver.removeresultsource(v=AX.60)
ms:contentKeyID: 62207682
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Common.FeatureReceiver.RemoveResultSource
dev_langs:
- CSharp
- C++
- VB
---

# RemoveResultSource Method

Removes ResultSource.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Common](microsoft-dynamics-retail-sharepoint-common-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Shared Sub RemoveResultSource ( _
    publishingPortalWeb As SPWeb, _
    name As String _
)
'Usage
Dim publishingPortalWeb As SPWeb
Dim name As String

FeatureReceiver.RemoveResultSource(publishingPortalWeb, _
    name)
```

``` csharp
public static void RemoveResultSource(
    SPWeb publishingPortalWeb,
    string name
)
```

``` c++
public:
static void RemoveResultSource(
    SPWeb^ publishingPortalWeb, 
    String^ name
)
```

#### Parameters

  - publishingPortalWeb  
    Type: SPWeb  

<!-- end list -->

  - name  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[FeatureReceiver Class](featurereceiver-class-microsoft-dynamics-retail-sharepoint-common.md)

[Microsoft.Dynamics.Retail.SharePoint.Common Namespace](microsoft-dynamics-retail-sharepoint-common-namespace.md)

