---
title: SharePointTimerJobHelper.WaitForOnetimeJobToFinish Method  (Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Job)
TOCTitle: WaitForOnetimeJobToFinish Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Job.SharePointTimerJobHelper.WaitForOnetimeJobToFinish(Microsoft.SharePoint.Administration.SPFarm,System.String,System.Byte)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sp.publishing.job.sharepointtimerjobhelper.waitforonetimejobtofinish(v=AX.60)
ms:contentKeyID: 65317995
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Job.SharePointTimerJobHelper.WaitForOnetimeJobToFinish
dev_langs:
- CSharp
- C++
- VB
---

# WaitForOnetimeJobToFinish Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Job](microsoft-dynamics-retail-ecommerce-sp-publishing-job-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Job (in Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Job.dll)

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

## See Also

#### Reference

[SharePointTimerJobHelper Class](sharepointtimerjobhelper-class-microsoft-dynamics-retail-ecommerce-sp-publishing-job.md)

[Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Job Namespace](microsoft-dynamics-retail-ecommerce-sp-publishing-job-namespace.md)

