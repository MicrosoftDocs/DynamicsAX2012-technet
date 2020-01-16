---
title: StockCountJournalTransaction.TrackingGuid Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TrackingGuid Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.StockCountJournalTransaction.TrackingGuid
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.stockcountjournaltransaction.trackingguid(v=AX.60)
ms:contentKeyID: 62209389
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.StockCountJournalTransaction.TrackingGuid
dev_langs:
- CSharp
- C++
- VB
---

# TrackingGuid Property

Gets or sets the tracking identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("TRACKINGGUID")> _
<DataMemberAttribute> _
Public Property TrackingGuid As Guid
    Get
    Set
'Usage
Dim instance As StockCountJournalTransaction
Dim value As Guid

value = instance.TrackingGuid

instance.TrackingGuid = value
```

``` csharp
[ColumnAttribute("TRACKINGGUID")]
[DataMemberAttribute]
public Guid TrackingGuid { get; set; }
```

``` c++
[ColumnAttribute(L"TRACKINGGUID")]
[DataMemberAttribute]
public:
property Guid TrackingGuid {
    Guid get ();
    void set (Guid value);
}
```

#### Property Value

Type: [System.Guid](https://technet.microsoft.com/library/cey1zx63\(v=ax.60\))  
Returns [Guid](https://technet.microsoft.com/library/cey1zx63\(v=ax.60\)).  

## See Also

#### Reference

[StockCountJournalTransaction Class](stockcountjournaltransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

