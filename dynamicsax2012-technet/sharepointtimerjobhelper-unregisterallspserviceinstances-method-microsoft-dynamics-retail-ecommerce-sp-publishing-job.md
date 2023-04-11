---
title: SharePointTimerJobHelper.UnregisterAllSPServiceInstances Method  (Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Job)
TOCTitle: UnregisterAllSPServiceInstances Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Job.SharePointTimerJobHelper.UnregisterAllSPServiceInstances(Microsoft.SharePoint.Administration.SPFarm,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sp.publishing.job.sharepointtimerjobhelper.unregisterallspserviceinstances(v=AX.60)
ms:contentKeyID: 65318516
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Job.SharePointTimerJobHelper.UnregisterAllSPServiceInstances
dev_langs:
- CSharp
- C++
- VB
---

# UnregisterAllSPServiceInstances Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Job](microsoft-dynamics-retail-ecommerce-sp-publishing-job-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Job (in Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Job.dll)

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

## See Also

#### Reference

[SharePointTimerJobHelper Class](sharepointtimerjobhelper-class-microsoft-dynamics-retail-ecommerce-sp-publishing-job.md)

[Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Job Namespace](microsoft-dynamics-retail-ecommerce-sp-publishing-job-namespace.md)

