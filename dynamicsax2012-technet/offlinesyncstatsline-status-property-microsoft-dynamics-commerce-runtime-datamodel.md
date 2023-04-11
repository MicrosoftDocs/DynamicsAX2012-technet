---
title: OfflineSyncStatsLine.Status Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Status Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.OfflineSyncStatsLine.Status
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.offlinesyncstatsline.status(v=AX.60)
ms:contentKeyID: 65321834
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.OfflineSyncStatsLine.Status
dev_langs:
- CSharp
- C++
- VB
---

# Status Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the last sync status.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("STATUS")> _
<DataMemberAttribute> _
Public Property Status As OfflineSyncStatus
    Get
    Set
'Usage
Dim instance As OfflineSyncStatsLine
Dim value As OfflineSyncStatus

value = instance.Status

instance.Status = value
```

``` csharp
[ColumnAttribute("STATUS")]
[DataMemberAttribute]
public OfflineSyncStatus Status { get; set; }
```

``` c++
[ColumnAttribute(L"STATUS")]
[DataMemberAttribute]
public:
property OfflineSyncStatus Status {
    OfflineSyncStatus get ();
    void set (OfflineSyncStatus value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.OfflineSyncStatus](offlinesyncstatus-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [OfflineSyncStatus](offlinesyncstatus-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[OfflineSyncStatsLine Class](offlinesyncstatsline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

