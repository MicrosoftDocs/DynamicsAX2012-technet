---
title: SharePointTimerJobHelper.TryGetSPService(T) Method  (Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Job)
TOCTitle: TryGetSPService(T) Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Job.SharePointTimerJobHelper.TryGetSPService``1(Microsoft.SharePoint.Administration.SPFarm,System.String,``0@)
ms:mtpsurl: https://technet.microsoft.com/library/Dn988704(v=AX.60)
ms:contentKeyID: 65318255
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Job.SharePointTimerJobHelper.TryGetSPService``1
dev_langs:
- CSharp
- C++
- VB
---

# TryGetSPService(T) Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Job](microsoft-dynamics-retail-ecommerce-sp-publishing-job-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Job (in Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Job.dll)

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
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - service  
    Type: T  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[SharePointTimerJobHelper Class](sharepointtimerjobhelper-class-microsoft-dynamics-retail-ecommerce-sp-publishing-job.md)

[Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Job Namespace](microsoft-dynamics-retail-ecommerce-sp-publishing-job-namespace.md)

