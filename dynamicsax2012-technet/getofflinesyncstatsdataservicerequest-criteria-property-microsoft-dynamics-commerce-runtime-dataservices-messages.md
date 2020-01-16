---
title: GetOfflineSyncStatsDataServiceRequest.Criteria Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: Criteria Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetOfflineSyncStatsDataServiceRequest.Criteria
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getofflinesyncstatsdataservicerequest.criteria(v=AX.60)
ms:contentKeyID: 65315733
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetOfflineSyncStatsDataServiceRequest.Criteria
dev_langs:
- CSharp
- C++
- VB
---

# Criteria Property

Gets query criteria.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Property Criteria As OfflineSyncStatsQueryCriteria
    Get
    Private Set
'Usage
Dim instance As GetOfflineSyncStatsDataServiceRequest
Dim value As OfflineSyncStatsQueryCriteria

value = instance.Criteria
```

``` csharp
public OfflineSyncStatsQueryCriteria Criteria { get; private set; }
```

``` c++
public:
property OfflineSyncStatsQueryCriteria^ Criteria {
    OfflineSyncStatsQueryCriteria^ get ();
    private: void set (OfflineSyncStatsQueryCriteria^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.OfflineSyncStatsQueryCriteria](offlinesyncstatsquerycriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [OfflineSyncStatsQueryCriteria](offlinesyncstatsquerycriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[GetOfflineSyncStatsDataServiceRequest Class](getofflinesyncstatsdataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

