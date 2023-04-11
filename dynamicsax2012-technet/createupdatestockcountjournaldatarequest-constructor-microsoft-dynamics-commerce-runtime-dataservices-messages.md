---
title: CreateUpdateStockCountJournalDataRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: CreateUpdateStockCountJournalDataRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.CreateUpdateStockCountJournalDataRequest.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.StockCountJournal})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.createupdatestockcountjournaldatarequest.createupdatestockcountjournaldatarequest(v=AX.60)
ms:contentKeyID: 65316173
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.CreateUpdateStockCountJournalDataRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# CreateUpdateStockCountJournalDataRequest Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [CreateUpdateStockCountJournalDataRequest](createupdatestockcountjournaldatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    journals As IEnumerable(Of StockCountJournal) _
)
'Usage
Dim journals As IEnumerable(Of StockCountJournal)

Dim instance As New CreateUpdateStockCountJournalDataRequest(journals)
```

``` csharp
public CreateUpdateStockCountJournalDataRequest(
    IEnumerable<StockCountJournal> journals
)
```

``` c++
public:
CreateUpdateStockCountJournalDataRequest(
    IEnumerable<StockCountJournal^>^ journals
)
```

#### Parameters

  - journals  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[StockCountJournal](stockcountjournal-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[CreateUpdateStockCountJournalDataRequest Class](createupdatestockcountjournaldatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

