---
title: CommitStockCountJournalRealtimeRequest.Journal Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: Journal Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CommitStockCountJournalRealtimeRequest.Journal
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.commitstockcountjournalrealtimerequest.journal(v=AX.60)
ms:contentKeyID: 65319473
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CommitStockCountJournalRealtimeRequest.Journal
dev_langs:
- CSharp
- C++
- VB
---

# Journal Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Journal As StockCountJournal
    Get
    Private Set
'Usage
Dim instance As CommitStockCountJournalRealtimeRequest
Dim value As StockCountJournal

value = instance.Journal
```

``` csharp
[DataMemberAttribute]
public StockCountJournal Journal { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property StockCountJournal^ Journal {
    StockCountJournal^ get ();
    private: void set (StockCountJournal^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.StockCountJournal](stockcountjournal-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[CommitStockCountJournalRealtimeRequest Class](commitstockcountjournalrealtimerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

