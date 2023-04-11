---
title: GetOfflineSyncStatsResponse.OfflineSyncStats Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: OfflineSyncStats Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetOfflineSyncStatsResponse.OfflineSyncStats
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getofflinesyncstatsresponse.offlinesyncstats(v=AX.60)
ms:contentKeyID: 65320766
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetOfflineSyncStatsResponse.OfflineSyncStats
dev_langs:
- CSharp
- C++
- VB
---

# OfflineSyncStats Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property OfflineSyncStats As ReadOnlyCollection(Of OfflineSyncStatsLine)
    Get
    Private Set
'Usage
Dim instance As GetOfflineSyncStatsResponse
Dim value As ReadOnlyCollection(Of OfflineSyncStatsLine)

value = instance.OfflineSyncStats
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<OfflineSyncStatsLine> OfflineSyncStats { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<OfflineSyncStatsLine^>^ OfflineSyncStats {
    ReadOnlyCollection<OfflineSyncStatsLine^>^ get ();
    private: void set (ReadOnlyCollection<OfflineSyncStatsLine^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[OfflineSyncStatsLine](offlinesyncstatsline-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetOfflineSyncStatsResponse Class](getofflinesyncstatsresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

