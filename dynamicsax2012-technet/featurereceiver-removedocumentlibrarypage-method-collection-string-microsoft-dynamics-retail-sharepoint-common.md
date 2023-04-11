---
title: FeatureReceiver.RemoveDocumentLibraryPage Method (, Collection(String)) (Microsoft.Dynamics.Retail.SharePoint.Common)
TOCTitle: RemoveDocumentLibraryPage Method (, Collection(String))
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Common.FeatureReceiver.RemoveDocumentLibraryPage(Microsoft.SharePoint.SPWeb,System.Collections.ObjectModel.Collection{System.String})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.common.featurereceiver.removedocumentlibrarypage(v=AX.60)
ms:contentKeyID: 62205473
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# RemoveDocumentLibraryPage Method (, Collection(String))


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Delete pages from the Pages document library.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Common](microsoft-dynamics-retail-sharepoint-common-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Shared Sub RemoveDocumentLibraryPage ( _
    web As SPWeb, _
    pageUrls As Collection(Of String) _
)
'Usage
Dim web As SPWeb
Dim pageUrls As Collection(Of String)

FeatureReceiver.RemoveDocumentLibraryPage(web, _
    pageUrls)
```

``` csharp
public static void RemoveDocumentLibraryPage(
    SPWeb web,
    Collection<string> pageUrls
)
```

``` c++
public:
static void RemoveDocumentLibraryPage(
    SPWeb^ web, 
    Collection<String^>^ pageUrls
)
```

#### Parameters

  - web  
    Type: SPWeb  

<!-- end list -->

  - pageUrls  
    Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/library/ms132397\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

## Exceptions

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>Exception</th>
<th>Condition</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><a href="https://technet.microsoft.com/library/27426hcy(v=ax.60)">ArgumentNullException</a></td>
<td><p>Thrown when the web parameter or pageUrls parameter is null.</p></td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[FeatureReceiver Class](featurereceiver-class-microsoft-dynamics-retail-sharepoint-common.md)

[RemoveDocumentLibraryPage Overload](featurereceiver-removedocumentlibrarypage-method-microsoft-dynamics-retail-sharepoint-common.md)

[Microsoft.Dynamics.Retail.SharePoint.Common Namespace](microsoft-dynamics-retail-sharepoint-common-namespace.md)

