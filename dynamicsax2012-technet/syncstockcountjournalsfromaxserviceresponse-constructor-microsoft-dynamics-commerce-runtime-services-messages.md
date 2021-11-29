---
title: SyncStockCountJournalsFromAxServiceResponse Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: SyncStockCountJournalsFromAxServiceResponse Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SyncStockCountJournalsFromAxServiceResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.StockCountJournal})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.syncstockcountjournalsfromaxserviceresponse.syncstockcountjournalsfromaxserviceresponse(v=AX.60)
ms:contentKeyID: 62214619
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SyncStockCountJournalsFromAxServiceResponse.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# SyncStockCountJournalsFromAxServiceResponse Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [SyncStockCountJournalsFromAxServiceResponse](syncstockcountjournalsfromaxserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    journals As IEnumerable(Of StockCountJournal) _
)
'Usage
Dim journals As IEnumerable(Of StockCountJournal)

Dim instance As New SyncStockCountJournalsFromAxServiceResponse(journals)
```

``` csharp
public SyncStockCountJournalsFromAxServiceResponse(
    IEnumerable<StockCountJournal> journals
)
```

``` c++
public:
SyncStockCountJournalsFromAxServiceResponse(
    IEnumerable<StockCountJournal^>^ journals
)
```

#### Parameters

  - journals  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[StockCountJournal](stockcountjournal-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[SyncStockCountJournalsFromAxServiceResponse Class](syncstockcountjournalsfromaxserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

