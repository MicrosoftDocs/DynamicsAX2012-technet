---
title: SharePointTimerJobHelper.UnregisterSPJobDefinition Method  (Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Job)
TOCTitle: UnregisterSPJobDefinition Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Job.SharePointTimerJobHelper.UnregisterSPJobDefinition(Microsoft.SharePoint.Administration.SPFarm,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sp.publishing.job.sharepointtimerjobhelper.unregisterspjobdefinition(v=AX.60)
ms:contentKeyID: 65317284
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Job.SharePointTimerJobHelper.UnregisterSPJobDefinition
dev_langs:
- CSharp
- C++
- VB
---

# UnregisterSPJobDefinition Method

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Job](microsoft-dynamics-retail-ecommerce-sp-publishing-job-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Job (in Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Job.dll)

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

## See Also

#### Reference

[SharePointTimerJobHelper Class](sharepointtimerjobhelper-class-microsoft-dynamics-retail-ecommerce-sp-publishing-job.md)

[Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Job Namespace](microsoft-dynamics-retail-ecommerce-sp-publishing-job-namespace.md)

