---
title: SaveStockCountRequest Constructor (String, IEnumerable(StockCountJournalTransaction), Boolean) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: SaveStockCountRequest Constructor (String, IEnumerable(StockCountJournalTransaction), Boolean)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.SaveStockCountRequest.#ctor(System.String,System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.StockCountJournalTransaction},System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.savestockcountrequest.savestockcountrequest(v=AX.60)
ms:contentKeyID: 62208572
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# SaveStockCountRequest Constructor (String, IEnumerable(StockCountJournalTransaction), Boolean)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [SaveStockCountRequest](savestockcountrequest-class-microsoft-dynamics-commerce-runtime-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    journalId As String, _
    stockCountJournalTransactionList As IEnumerable(Of StockCountJournalTransaction), _
    isCommitted As Boolean _
)
'Usage
Dim journalId As String
Dim stockCountJournalTransactionList As IEnumerable(Of StockCountJournalTransaction)
Dim isCommitted As Boolean

Dim instance As New SaveStockCountRequest(journalId, _
    stockCountJournalTransactionList, _
    isCommitted)
```

``` csharp
public SaveStockCountRequest(
    string journalId,
    IEnumerable<StockCountJournalTransaction> stockCountJournalTransactionList,
    bool isCommitted
)
```

``` c++
public:
SaveStockCountRequest(
    String^ journalId, 
    IEnumerable<StockCountJournalTransaction^>^ stockCountJournalTransactionList, 
    bool isCommitted
)
```

#### Parameters

  - journalId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - stockCountJournalTransactionList  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[StockCountJournalTransaction](stockcountjournaltransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

<!-- end list -->

  - isCommitted  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[SaveStockCountRequest Class](savestockcountrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[SaveStockCountRequest Overload](savestockcountrequest-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

