---
title: SharePointTimerJobHelper.TryGetSPServiceInstance(T) Method  (Microsoft.Dynamics.Retail.SharePoint.Common)
TOCTitle: TryGetSPServiceInstance(T) Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Common.SharePointTimerJobHelper.TryGetSPServiceInstance``1(Microsoft.SharePoint.Administration.SPServer,System.String,``0@)
ms:mtpsurl: https://technet.microsoft.com/library/Dn717117(v=AX.60)
ms:contentKeyID: 62205911
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Common.SharePointTimerJobHelper.TryGetSPServiceInstance``1
dev_langs:
- CSharp
- C++
- VB
---

# TryGetSPServiceInstance(T) Method

Tries to get the SPServiceInstance by name and server.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Common](microsoft-dynamics-retail-sharepoint-common-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Shared Function TryGetSPServiceInstance(Of T As SPServiceInstance) ( _
    server As SPServer, _
    serviceInstanceName As String, _
    <OutAttribute> ByRef serviceInstance As T _
) As Boolean
'Usage
Dim server As SPServer
Dim serviceInstanceName As String
Dim serviceInstance As T
Dim returnValue As Boolean

returnValue = SharePointTimerJobHelper.TryGetSPServiceInstance(server, _
    serviceInstanceName, serviceInstance)
```

``` csharp
public static bool TryGetSPServiceInstance<T>(
    SPServer server,
    string serviceInstanceName,
    out T serviceInstance
)
where T : SPServiceInstance
```

``` c++
public:
generic<typename T>
where T : SPServiceInstance
static bool TryGetSPServiceInstance(
    SPServer^ server, 
    String^ serviceInstanceName, 
    [OutAttribute] T% serviceInstance
)
```

#### Type Parameters

  - T

#### Parameters

  - server  
    Type: SPServer  

<!-- end list -->

  - serviceInstanceName  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - serviceInstance  
    Type: T  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
True if the specificed service instance is found, else false.  

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
<td><p>server or serviceInstanceName</p></td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[SharePointTimerJobHelper Class](sharepointtimerjobhelper-class-microsoft-dynamics-retail-sharepoint-common.md)

[Microsoft.Dynamics.Retail.SharePoint.Common Namespace](microsoft-dynamics-retail-sharepoint-common-namespace.md)

