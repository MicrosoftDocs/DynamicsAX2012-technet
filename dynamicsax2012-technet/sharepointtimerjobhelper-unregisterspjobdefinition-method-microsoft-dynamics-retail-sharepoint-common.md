---
title: SharePointTimerJobHelper.UnregisterSPJobDefinition Method  (Microsoft.Dynamics.Retail.SharePoint.Common)
TOCTitle: UnregisterSPJobDefinition Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Common.SharePointTimerJobHelper.UnregisterSPJobDefinition(Microsoft.SharePoint.Administration.SPFarm,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.common.sharepointtimerjobhelper.unregisterspjobdefinition(v=AX.60)
ms:contentKeyID: 62203788
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Common.SharePointTimerJobHelper.UnregisterSPJobDefinition
dev_langs:
- CSharp
- C++
- VB
---

# UnregisterSPJobDefinition Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Unregisters a job from a service.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Common](microsoft-dynamics-retail-sharepoint-common-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Shared Sub UnregisterSPJobDefinition ( _
    farm As SPFarm, _
    serviceName As String, _
    jobName As String _
)
'Usage
Dim farm As SPFarm
Dim serviceName As String
Dim jobName As String

SharePointTimerJobHelper.UnregisterSPJobDefinition(farm, _
    serviceName, jobName)
```

``` csharp
public static void UnregisterSPJobDefinition(
    SPFarm farm,
    string serviceName,
    string jobName
)
```

``` c++
public:
static void UnregisterSPJobDefinition(
    SPFarm^ farm, 
    String^ serviceName, 
    String^ jobName
)
```

#### Parameters

  - farm  
    Type: SPFarm  

<!-- end list -->

  - serviceName  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - jobName  
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
<td><p>farm or serviceName</p></td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[SharePointTimerJobHelper Class](sharepointtimerjobhelper-class-microsoft-dynamics-retail-sharepoint-common.md)

[Microsoft.Dynamics.Retail.SharePoint.Common Namespace](microsoft-dynamics-retail-sharepoint-common-namespace.md)

