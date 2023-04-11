---
title: SharePointTimerJobHelper.TryGetSPServiceInstance(T) Method  (Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Job)
TOCTitle: TryGetSPServiceInstance(T) Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Job.SharePointTimerJobHelper.TryGetSPServiceInstance``1(Microsoft.SharePoint.Administration.SPServer,System.String,``0@)
ms:mtpsurl: https://technet.microsoft.com/library/Dn988757(v=AX.60)
ms:contentKeyID: 65318308
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Job.SharePointTimerJobHelper.TryGetSPServiceInstance``1
dev_langs:
- CSharp
- C++
- VB
---

# TryGetSPServiceInstance(T) Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Job](microsoft-dynamics-retail-ecommerce-sp-publishing-job-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Job (in Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Job.dll)

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

## See Also

#### Reference

[SharePointTimerJobHelper Class](sharepointtimerjobhelper-class-microsoft-dynamics-retail-ecommerce-sp-publishing-job.md)

[Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Job Namespace](microsoft-dynamics-retail-ecommerce-sp-publishing-job-namespace.md)

