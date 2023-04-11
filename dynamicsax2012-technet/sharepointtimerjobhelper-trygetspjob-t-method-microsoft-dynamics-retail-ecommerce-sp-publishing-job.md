---
title: SharePointTimerJobHelper.TryGetSPJob(T) Method  (Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Job)
TOCTitle: TryGetSPJob(T) Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Job.SharePointTimerJobHelper.TryGetSPJob``1(Microsoft.SharePoint.Administration.SPService,System.String,``0@)
ms:mtpsurl: https://technet.microsoft.com/library/Dn966844(v=AX.60)
ms:contentKeyID: 65317707
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Job.SharePointTimerJobHelper.TryGetSPJob``1
dev_langs:
- CSharp
- C++
- VB
---

# TryGetSPJob(T) Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Job](microsoft-dynamics-retail-ecommerce-sp-publishing-job-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Job (in Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Job.dll)

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

## See Also

#### Reference

[SharePointTimerJobHelper Class](sharepointtimerjobhelper-class-microsoft-dynamics-retail-ecommerce-sp-publishing-job.md)

[Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Job Namespace](microsoft-dynamics-retail-ecommerce-sp-publishing-job-namespace.md)

