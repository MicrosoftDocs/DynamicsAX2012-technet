---
title: SharePointTimerJobHelper.UnregisterAllSPServiceInstances Method  (Microsoft.Dynamics.Retail.SharePoint.Common)
TOCTitle: UnregisterAllSPServiceInstances Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Common.SharePointTimerJobHelper.UnregisterAllSPServiceInstances(Microsoft.SharePoint.Administration.SPFarm,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.common.sharepointtimerjobhelper.unregisterallspserviceinstances(v=AX.60)
ms:contentKeyID: 62206225
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Common.SharePointTimerJobHelper.UnregisterAllSPServiceInstances
dev_langs:
- CSharp
- C++
- VB
---

# UnregisterAllSPServiceInstances Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Unregisters all service instances of a service.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Common](microsoft-dynamics-retail-sharepoint-common-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Shared Sub UnregisterAllSPServiceInstances ( _
    farm As SPFarm, _
    serviceName As String, _
    serviceInstanceName As String _
)
'Usage
Dim farm As SPFarm
Dim serviceName As String
Dim serviceInstanceName As String

SharePointTimerJobHelper.UnregisterAllSPServiceInstances(farm, _
    serviceName, serviceInstanceName)
```

``` csharp
public static void UnregisterAllSPServiceInstances(
    SPFarm farm,
    string serviceName,
    string serviceInstanceName
)
```

``` c++
public:
static void UnregisterAllSPServiceInstances(
    SPFarm^ farm, 
    String^ serviceName, 
    String^ serviceInstanceName
)
```

#### Parameters

  - farm  
    Type: SPFarm  

<!-- end list -->

  - serviceName  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - serviceInstanceName  
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
<td><p>farm or serviceName or serviceInstanceName</p></td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[SharePointTimerJobHelper Class](sharepointtimerjobhelper-class-microsoft-dynamics-retail-sharepoint-common.md)

[Microsoft.Dynamics.Retail.SharePoint.Common Namespace](microsoft-dynamics-retail-sharepoint-common-namespace.md)

