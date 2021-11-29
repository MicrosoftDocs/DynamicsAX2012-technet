---
title: StockCountJournalTransaction.CountedDate Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CountedDate Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.StockCountJournalTransaction.CountedDate
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.stockcountjournaltransaction.counteddate(v=AX.60)
ms:contentKeyID: 62212281
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.StockCountJournalTransaction.CountedDate
dev_langs:
- CSharp
- C++
- VB
---

# CountedDate Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the counted date.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("COUNTEDDATE")> _
<DataMemberAttribute> _
Public Property CountedDate As Nullable(Of DateTimeOffset)
    Get
    Set
'Usage
Dim instance As StockCountJournalTransaction
Dim value As Nullable(Of DateTimeOffset)

value = instance.CountedDate

instance.CountedDate = value
```

``` csharp
[ColumnAttribute("COUNTEDDATE")]
[DataMemberAttribute]
public Nullable<DateTimeOffset> CountedDate { get; set; }
```

``` c++
[ColumnAttribute(L"COUNTEDDATE")]
[DataMemberAttribute]
public:
property Nullable<DateTimeOffset> CountedDate {
    Nullable<DateTimeOffset> get ();
    void set (Nullable<DateTimeOffset> value);
}
```

#### Property Value

Type: [System.Nullable](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\))\<[DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))\>  
Returns [Nullable\<T\>](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\)).  

## See Also

#### Reference

[StockCountJournalTransaction Class](stockcountjournaltransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

