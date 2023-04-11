---
title: SharePointTimerJobHelper.GetOnlineFarmServersWithTimerInstance Method  (Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Job)
TOCTitle: GetOnlineFarmServersWithTimerInstance Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Job.SharePointTimerJobHelper.GetOnlineFarmServersWithTimerInstance(Microsoft.SharePoint.Administration.SPFarm)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sp.publishing.job.sharepointtimerjobhelper.getonlinefarmserverswithtimerinstance(v=AX.60)
ms:contentKeyID: 65317016
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Job.SharePointTimerJobHelper.GetOnlineFarmServersWithTimerInstance
dev_langs:
- CSharp
- C++
- VB
---

# GetOnlineFarmServersWithTimerInstance Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Job](microsoft-dynamics-retail-ecommerce-sp-publishing-job-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Job (in Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Job.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GetOnlineFarmServersWithTimerInstance ( _
    farm As SPFarm _
) As IEnumerable(Of SPServer)
'Usage
Dim farm As SPFarm
Dim returnValue As IEnumerable(Of SPServer)

returnValue = SharePointTimerJobHelper.GetOnlineFarmServersWithTimerInstance(farm)
```

``` csharp
public static IEnumerable<SPServer> GetOnlineFarmServersWithTimerInstance(
    SPFarm farm
)
```

``` c++
public:
static IEnumerable<SPServer^>^ GetOnlineFarmServersWithTimerInstance(
    SPFarm^ farm
)
```

#### Parameters

  - farm  
    Type: SPFarm  

#### Return Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<SPServer\>  

## See Also

#### Reference

[SharePointTimerJobHelper Class](sharepointtimerjobhelper-class-microsoft-dynamics-retail-ecommerce-sp-publishing-job.md)

[Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Job Namespace](microsoft-dynamics-retail-ecommerce-sp-publishing-job-namespace.md)

