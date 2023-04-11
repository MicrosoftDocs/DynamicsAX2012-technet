---
title: FeatureReceiver.RemoveAllWebParts Method  (Microsoft.Dynamics.Retail.SharePoint.Common)
TOCTitle: RemoveAllWebParts Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Common.FeatureReceiver.RemoveAllWebParts(Microsoft.SharePoint.SPWeb,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.common.featurereceiver.removeallwebparts(v=AX.60)
ms:contentKeyID: 62203291
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Common.FeatureReceiver.RemoveAllWebParts
dev_langs:
- CSharp
- C++
- VB
---

# RemoveAllWebParts Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Removes all web parts from the page and zone.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Common](microsoft-dynamics-retail-sharepoint-common-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Shared Sub RemoveAllWebParts ( _
    web As SPWeb, _
    pageName As String _
)
'Usage
Dim web As SPWeb
Dim pageName As String

FeatureReceiver.RemoveAllWebParts(web, pageName)
```

``` csharp
public static void RemoveAllWebParts(
    SPWeb web,
    string pageName
)
```

``` c++
public:
static void RemoveAllWebParts(
    SPWeb^ web, 
    String^ pageName
)
```

#### Parameters

  - web  
    Type: SPWeb  

<!-- end list -->

  - pageName  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

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
<td><p>Thrown when the web parameter is null or when the pageName parameter is null or empty.</p></td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[FeatureReceiver Class](featurereceiver-class-microsoft-dynamics-retail-sharepoint-common.md)

[Microsoft.Dynamics.Retail.SharePoint.Common Namespace](microsoft-dynamics-retail-sharepoint-common-namespace.md)

