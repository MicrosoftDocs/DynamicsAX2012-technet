---
title: FeatureReceiver.RemoveDocumentLibraryPage Method (, String) (Microsoft.Dynamics.Retail.SharePoint.Common)
TOCTitle: RemoveDocumentLibraryPage Method (, String)
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Common.FeatureReceiver.RemoveDocumentLibraryPage(Microsoft.SharePoint.SPWeb,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.common.featurereceiver.removedocumentlibrarypage(v=AX.60)
ms:contentKeyID: 62206205
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# RemoveDocumentLibraryPage Method (, String)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Delete a page from the Pages document library.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Common](microsoft-dynamics-retail-sharepoint-common-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Shared Sub RemoveDocumentLibraryPage ( _
    web As SPWeb, _
    pageUrl As String _
)
'Usage
Dim web As SPWeb
Dim pageUrl As String

FeatureReceiver.RemoveDocumentLibraryPage(web, _
    pageUrl)
```

``` csharp
public static void RemoveDocumentLibraryPage(
    SPWeb web,
    string pageUrl
)
```

``` c++
public:
static void RemoveDocumentLibraryPage(
    SPWeb^ web, 
    String^ pageUrl
)
```

#### Parameters

  - web  
    Type: SPWeb  

<!-- end list -->

  - pageUrl  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[FeatureReceiver Class](featurereceiver-class-microsoft-dynamics-retail-sharepoint-common.md)

[RemoveDocumentLibraryPage Overload](featurereceiver-removedocumentlibrarypage-method-microsoft-dynamics-retail-sharepoint-common.md)

[Microsoft.Dynamics.Retail.SharePoint.Common Namespace](microsoft-dynamics-retail-sharepoint-common-namespace.md)

