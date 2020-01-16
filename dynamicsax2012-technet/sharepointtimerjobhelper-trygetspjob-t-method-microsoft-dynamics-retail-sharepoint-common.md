---
title: SharePointTimerJobHelper.TryGetSPJob(T) Method  (Microsoft.Dynamics.Retail.SharePoint.Common)
TOCTitle: TryGetSPJob(T) Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Common.SharePointTimerJobHelper.TryGetSPJob``1(Microsoft.SharePoint.Administration.SPService,System.String,``0@)
ms:mtpsurl: https://technet.microsoft.com/library/Dn717421(v=AX.60)
ms:contentKeyID: 62206213
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Common.SharePointTimerJobHelper.TryGetSPJob``1
dev_langs:
- CSharp
- C++
- VB
---

# TryGetSPJob(T) Method

Tries to get the SPJobDefinition by name.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Common](microsoft-dynamics-retail-sharepoint-common-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Shared Function TryGetSPJob(Of T As SPJobDefinition) ( _
    service As SPService, _
    jobName As String, _
    <OutAttribute> ByRef job As T _
) As Boolean
'Usage
Dim service As SPService
Dim jobName As String
Dim job As T
Dim returnValue As Boolean

returnValue = SharePointTimerJobHelper.TryGetSPJob(service, _
    jobName, job)
```

``` csharp
public static bool TryGetSPJob<T>(
    SPService service,
    string jobName,
    out T job
)
where T : SPJobDefinition
```

``` c++
public:
generic<typename T>
where T : SPJobDefinition
static bool TryGetSPJob(
    SPService^ service, 
    String^ jobName, 
    [OutAttribute] T% job
)
```

#### Type Parameters

  - T

#### Parameters

  - service  
    Type: SPService  

<!-- end list -->

  - jobName  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - job  
    Type: T  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
True if the specificed job name was found, else false.  

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
<td><p>service or jobName</p></td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[SharePointTimerJobHelper Class](sharepointtimerjobhelper-class-microsoft-dynamics-retail-sharepoint-common.md)

[Microsoft.Dynamics.Retail.SharePoint.Common Namespace](microsoft-dynamics-retail-sharepoint-common-namespace.md)

