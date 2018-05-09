---
title: FeatureReceiver.SetDefaultPage Method  (Microsoft.Dynamics.Retail.SharePoint.Common)
TOCTitle: SetDefaultPage Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Common.FeatureReceiver.SetDefaultPage(Microsoft.SharePoint.SPWeb,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.common.featurereceiver.setdefaultpage(v=AX.60)
ms:contentKeyID: 62206376
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Common.FeatureReceiver.SetDefaultPage
dev_langs:
- CSharp
- C++
- VB
---

# SetDefaultPage Method

Sets the default welcome page to the specified SharePoint site.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Common](microsoft-dynamics-retail-sharepoint-common-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Shared Sub SetDefaultPage ( _
    web As SPWeb, _
    pageName As String _
)
'Usage
Dim web As SPWeb
Dim pageName As String

FeatureReceiver.SetDefaultPage(web, pageName)
```

``` csharp
public static void SetDefaultPage(
    SPWeb web,
    string pageName
)
```

``` c++
public:
static void SetDefaultPage(
    SPWeb^ web, 
    String^ pageName
)
```

#### Parameters

  - web  
    Type: SPWeb  

<!-- end list -->

  - pageName  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

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
<td><a href="https://technet.microsoft.com/en-us/library/27426hcy(v=ax.60)">ArgumentNullException</a></td>
<td><p>Thrown when the web parameter is null or when the pageName parameter is null or empty.</p></td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[FeatureReceiver Class](featurereceiver-class-microsoft-dynamics-retail-sharepoint-common.md)

[Microsoft.Dynamics.Retail.SharePoint.Common Namespace](microsoft-dynamics-retail-sharepoint-common-namespace.md)

