---
title: OfflineSyncStatsLine.LastSyncDateTime Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LastSyncDateTime Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.OfflineSyncStatsLine.LastSyncDateTime
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.offlinesyncstatsline.lastsyncdatetime(v=AX.60)
ms:contentKeyID: 65322043
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.OfflineSyncStatsLine.LastSyncDateTime
dev_langs:
- CSharp
- C++
- VB
---

# LastSyncDateTime Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the last sync timestamp.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("LASTSYNCDATETIME")> _
Public Property LastSyncDateTime As DateTimeOffset
    Get
    Set
'Usage
Dim instance As OfflineSyncStatsLine
Dim value As DateTimeOffset

value = instance.LastSyncDateTime

instance.LastSyncDateTime = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("LASTSYNCDATETIME")]
public DateTimeOffset LastSyncDateTime { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"LASTSYNCDATETIME")]
public:
property DateTimeOffset LastSyncDateTime {
    DateTimeOffset get ();
    void set (DateTimeOffset value);
}
```

#### Property Value

Type: [System.DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))  
Returns [DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\)).  

## See Also

#### Reference

[OfflineSyncStatsLine Class](offlinesyncstatsline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

