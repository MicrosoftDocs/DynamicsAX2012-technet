---
title: GetOfflineSyncStatsResponse Constructor (ReadOnlyCollection(OfflineSyncStatsLine)) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetOfflineSyncStatsResponse Constructor (ReadOnlyCollection(OfflineSyncStatsLine))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetOfflineSyncStatsResponse.#ctor(System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.OfflineSyncStatsLine})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getofflinesyncstatsresponse.getofflinesyncstatsresponse(v=AX.60)
ms:contentKeyID: 65323059
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetOfflineSyncStatsResponse Constructor (ReadOnlyCollection(OfflineSyncStatsLine))


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    offlineSyncStats As ReadOnlyCollection(Of OfflineSyncStatsLine) _
)
'Usage
Dim offlineSyncStats As ReadOnlyCollection(Of OfflineSyncStatsLine)

Dim instance As New GetOfflineSyncStatsResponse(offlineSyncStats)
```

``` csharp
public GetOfflineSyncStatsResponse(
    ReadOnlyCollection<OfflineSyncStatsLine> offlineSyncStats
)
```

``` c++
public:
GetOfflineSyncStatsResponse(
    ReadOnlyCollection<OfflineSyncStatsLine^>^ offlineSyncStats
)
```

#### Parameters

  - offlineSyncStats  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[OfflineSyncStatsLine](offlinesyncstatsline-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetOfflineSyncStatsResponse Class](getofflinesyncstatsresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[GetOfflineSyncStatsResponse Overload](getofflinesyncstatsresponse-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

