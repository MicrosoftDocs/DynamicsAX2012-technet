---
title: SaveStockCountRequest.StockCountJournalTransactionList Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: StockCountJournalTransactionList Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.SaveStockCountRequest.StockCountJournalTransactionList
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.savestockcountrequest.stockcountjournaltransactionlist(v=AX.60)
ms:contentKeyID: 62210340
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.SaveStockCountRequest.StockCountJournalTransactionList
dev_langs:
- CSharp
- C++
- VB
---

# StockCountJournalTransactionList Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets StockCountJournal transaction collection.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property StockCountJournalTransactionList As ReadOnlyCollection(Of StockCountJournalTransaction)
    Get
    Private Set
'Usage
Dim instance As SaveStockCountRequest
Dim value As ReadOnlyCollection(Of StockCountJournalTransaction)

value = instance.StockCountJournalTransactionList
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<StockCountJournalTransaction> StockCountJournalTransactionList { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<StockCountJournalTransaction^>^ StockCountJournalTransactionList {
    ReadOnlyCollection<StockCountJournalTransaction^>^ get ();
    private: void set (ReadOnlyCollection<StockCountJournalTransaction^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[StockCountJournalTransaction](stockcountjournaltransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[SaveStockCountRequest Class](savestockcountrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

