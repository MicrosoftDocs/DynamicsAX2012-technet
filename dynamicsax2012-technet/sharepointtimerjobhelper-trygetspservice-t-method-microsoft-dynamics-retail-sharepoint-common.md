---
title: SharePointTimerJobHelper.TryGetSPService(T) Method  (Microsoft.Dynamics.Retail.SharePoint.Common)
TOCTitle: TryGetSPService(T) Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Common.SharePointTimerJobHelper.TryGetSPService``1(Microsoft.SharePoint.Administration.SPFarm,System.String,``0@)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn694632(v=AX.60)
ms:contentKeyID: 62205044
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Common.SharePointTimerJobHelper.TryGetSPService``1
dev_langs:
- CSharp
- C++
- VB
---

# TryGetSPService(T) Method

Tries to get the SPService by name.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Common](microsoft-dynamics-retail-sharepoint-common-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Shared Function TryGetSPService(Of T As SPService) ( _
    farm As SPFarm, _
    serviceName As String, _
    <OutAttribute> ByRef service As T _
) As Boolean
'Usage
Dim farm As SPFarm
Dim serviceName As String
Dim service As T
Dim returnValue As Boolean

returnValue = SharePointTimerJobHelper.TryGetSPService(farm, _
    serviceName, service)
```

``` csharp
public static bool TryGetSPService<T>(
    SPFarm farm,
    string serviceName,
    out T service
)
where T : SPService
```

``` c++
public:
generic<typename T>
where T : SPService
static bool TryGetSPService(
    SPFarm^ farm, 
    String^ serviceName, 
    [OutAttribute] T% service
)
```

#### Type Parameters

  - T

#### Parameters

  - farm  
    Type: SPFarm  

<!-- end list -->

  - serviceName  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - service  
    Type: T  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
True if the specified service was found, else false.  

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
<td><p>farm or serviceName</p></td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[SharePointTimerJobHelper Class](sharepointtimerjobhelper-class-microsoft-dynamics-retail-sharepoint-common.md)

[Microsoft.Dynamics.Retail.SharePoint.Common Namespace](microsoft-dynamics-retail-sharepoint-common-namespace.md)

