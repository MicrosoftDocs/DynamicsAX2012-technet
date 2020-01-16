---
title: StockCountJournal.StockCountTransactionLines Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: StockCountTransactionLines Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.StockCountJournal.StockCountTransactionLines
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.stockcountjournal.stockcounttransactionlines(v=AX.60)
ms:contentKeyID: 62213131
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.StockCountJournal.StockCountTransactionLines
dev_langs:
- CSharp
- C++
- VB
---

# StockCountTransactionLines Property

Gets or sets the StockCountTransactionLines.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property StockCountTransactionLines As ICollection(Of StockCountJournalTransaction)
    Get
    Set
'Usage
Dim instance As StockCountJournal
Dim value As ICollection(Of StockCountJournalTransaction)

value = instance.StockCountTransactionLines

instance.StockCountTransactionLines = value
```

``` csharp
[DataMemberAttribute]
public ICollection<StockCountJournalTransaction> StockCountTransactionLines { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property ICollection<StockCountJournalTransaction^>^ StockCountTransactionLines {
    ICollection<StockCountJournalTransaction^>^ get ();
    void set (ICollection<StockCountJournalTransaction^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\))\<[StockCountJournalTransaction](stockcountjournaltransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ICollection\<T\>](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\)).  

## See Also

#### Reference

[StockCountJournal Class](stockcountjournal-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

