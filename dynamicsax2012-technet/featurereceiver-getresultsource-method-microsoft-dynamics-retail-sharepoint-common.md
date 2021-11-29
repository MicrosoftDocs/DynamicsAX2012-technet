---
title: FeatureReceiver.GetResultSource Method  (Microsoft.Dynamics.Retail.SharePoint.Common)
TOCTitle: GetResultSource Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Common.FeatureReceiver.GetResultSource(Microsoft.SharePoint.SPWeb,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.common.featurereceiver.getresultsource(v=AX.60)
ms:contentKeyID: 62206687
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Common.FeatureReceiver.GetResultSource
dev_langs:
- CSharp
- C++
- VB
---

# GetResultSource Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the result source.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Common](microsoft-dynamics-retail-sharepoint-common-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GetResultSource ( _
    publishingPortalWeb As SPWeb, _
    name As String _
) As Source
'Usage
Dim publishingPortalWeb As SPWeb
Dim name As String
Dim returnValue As Source

returnValue = FeatureReceiver.GetResultSource(publishingPortalWeb, _
    name)
```

``` csharp
public static Source GetResultSource(
    SPWeb publishingPortalWeb,
    string name
)
```

``` c++
public:
static Source^ GetResultSource(
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

#### Return Value

Type: Source  
The Source instance.  

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
<td><a href="https://technet.microsoft.com/library/2asft85a(v=ax.60)">InvalidOperationException</a></td>
<td><p>Thrown when the source cannot be found.</p></td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[FeatureReceiver Class](featurereceiver-class-microsoft-dynamics-retail-sharepoint-common.md)

[Microsoft.Dynamics.Retail.SharePoint.Common Namespace](microsoft-dynamics-retail-sharepoint-common-namespace.md)

