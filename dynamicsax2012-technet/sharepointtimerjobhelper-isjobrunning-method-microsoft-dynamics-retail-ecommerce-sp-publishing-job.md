---
title: SharePointTimerJobHelper.IsJobRunning Method  (Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Job)
TOCTitle: IsJobRunning Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Job.SharePointTimerJobHelper.IsJobRunning(Microsoft.SharePoint.Administration.SPFarm,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sp.publishing.job.sharepointtimerjobhelper.isjobrunning(v=AX.60)
ms:contentKeyID: 65317946
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Job.SharePointTimerJobHelper.IsJobRunning
dev_langs:
- CSharp
- C++
- VB
---

# IsJobRunning Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Job](microsoft-dynamics-retail-ecommerce-sp-publishing-job-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Job (in Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Job.dll)

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
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[SharePointTimerJobHelper Class](sharepointtimerjobhelper-class-microsoft-dynamics-retail-ecommerce-sp-publishing-job.md)

[Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Job Namespace](microsoft-dynamics-retail-ecommerce-sp-publishing-job-namespace.md)

