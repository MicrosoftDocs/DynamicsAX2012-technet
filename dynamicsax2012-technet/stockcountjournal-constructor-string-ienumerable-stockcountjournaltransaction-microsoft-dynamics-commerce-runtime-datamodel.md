---
title: StockCountJournal Constructor (String, IEnumerable(StockCountJournalTransaction)) (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: StockCountJournal Constructor (String, IEnumerable(StockCountJournalTransaction))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.StockCountJournal.#ctor(System.String,System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.StockCountJournalTransaction})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.stockcountjournal.stockcountjournal(v=AX.60)
ms:contentKeyID: 62209133
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# StockCountJournal Constructor (String, IEnumerable(StockCountJournalTransaction))

Initializes a new instance of the [StockCountJournal](stockcountjournal-class-microsoft-dynamics-commerce-runtime-datamodel.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    journalId As String, _
    transactions As IEnumerable(Of StockCountJournalTransaction) _
)
'Usage
Dim journalId As String
Dim transactions As IEnumerable(Of StockCountJournalTransaction)

Dim instance As New StockCountJournal(journalId, _
    transactions)
```

``` csharp
public StockCountJournal(
    string journalId,
    IEnumerable<StockCountJournalTransaction> transactions
)
```

``` c++
public:
StockCountJournal(
    String^ journalId, 
    IEnumerable<StockCountJournalTransaction^>^ transactions
)
```

#### Parameters

  - journalId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - transactions  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[StockCountJournalTransaction](stockcountjournaltransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[StockCountJournal Class](stockcountjournal-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[StockCountJournal Overload](stockcountjournal-constructor-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

