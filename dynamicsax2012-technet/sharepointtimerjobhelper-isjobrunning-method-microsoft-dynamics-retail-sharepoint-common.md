---
title: SharePointTimerJobHelper.IsJobRunning Method  (Microsoft.Dynamics.Retail.SharePoint.Common)
TOCTitle: IsJobRunning Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Common.SharePointTimerJobHelper.IsJobRunning(Microsoft.SharePoint.Administration.SPFarm,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.common.sharepointtimerjobhelper.isjobrunning(v=AX.60)
ms:contentKeyID: 62205326
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Common.SharePointTimerJobHelper.IsJobRunning
dev_langs:
- CSharp
- C++
- VB
---

# IsJobRunning Method

Checks if a job is running.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Common](microsoft-dynamics-retail-sharepoint-common-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Shared Function IsJobRunning ( _
    farm As SPFarm, _
    jobTitle As String _
) As Boolean
'Usage
Dim farm As SPFarm
Dim jobTitle As String
Dim returnValue As Boolean

returnValue = SharePointTimerJobHelper.IsJobRunning(farm, _
    jobTitle)
```

``` csharp
public static bool IsJobRunning(
    SPFarm farm,
    string jobTitle
)
```

``` c++
public:
static bool IsJobRunning(
    SPFarm^ farm, 
    String^ jobTitle
)
```

#### Parameters

  - farm  
    Type: SPFarm  

<!-- end list -->

  - jobTitle  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
true if the job is running in the specified farm; otherwise, false.  

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
<td><p>farm or jobTitle</p></td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[SharePointTimerJobHelper Class](sharepointtimerjobhelper-class-microsoft-dynamics-retail-sharepoint-common.md)

[Microsoft.Dynamics.Retail.SharePoint.Common Namespace](microsoft-dynamics-retail-sharepoint-common-namespace.md)

