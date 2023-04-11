---
title: SharePointTimerJobHelper.WaitForOnetimeJobToFinish Method  (Microsoft.Dynamics.Retail.SharePoint.Common)
TOCTitle: WaitForOnetimeJobToFinish Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Common.SharePointTimerJobHelper.WaitForOnetimeJobToFinish(Microsoft.SharePoint.Administration.SPFarm,System.String,System.Byte)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.common.sharepointtimerjobhelper.waitforonetimejobtofinish(v=AX.60)
ms:contentKeyID: 62202553
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Common.SharePointTimerJobHelper.WaitForOnetimeJobToFinish
dev_langs:
- CSharp
- C++
- VB
---

# WaitForOnetimeJobToFinish Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Waits for the Job to finish.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Common](microsoft-dynamics-retail-sharepoint-common-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Shared Sub WaitForOnetimeJobToFinish ( _
    farm As SPFarm, _
    jobTitle As String, _
    maximumWaitTime As Byte _
)
'Usage
Dim farm As SPFarm
Dim jobTitle As String
Dim maximumWaitTime As Byte

SharePointTimerJobHelper.WaitForOnetimeJobToFinish(farm, _
    jobTitle, maximumWaitTime)
```

``` csharp
public static void WaitForOnetimeJobToFinish(
    SPFarm farm,
    string jobTitle,
    byte maximumWaitTime
)
```

``` c++
public:
static void WaitForOnetimeJobToFinish(
    SPFarm^ farm, 
    String^ jobTitle, 
    unsigned char maximumWaitTime
)
```

#### Parameters

  - farm  
    Type: SPFarm  

<!-- end list -->

  - jobTitle  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - maximumWaitTime  
    Type: [System.Byte](https://technet.microsoft.com/library/yyb1w04y\(v=ax.60\))  

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
<td><p>farm or jobTitle</p></td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[SharePointTimerJobHelper Class](sharepointtimerjobhelper-class-microsoft-dynamics-retail-sharepoint-common.md)

[Microsoft.Dynamics.Retail.SharePoint.Common Namespace](microsoft-dynamics-retail-sharepoint-common-namespace.md)

