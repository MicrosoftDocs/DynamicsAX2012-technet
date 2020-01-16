---
title: SaveStockCountJournalTransactionServiceResponse.StockCountJournal Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: StockCountJournal Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SaveStockCountJournalTransactionServiceResponse.StockCountJournal
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.savestockcountjournaltransactionserviceresponse.stockcountjournal(v=AX.60)
ms:contentKeyID: 62202390
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SaveStockCountJournalTransactionServiceResponse.StockCountJournal
dev_langs:
- CSharp
- C++
- VB
---

# StockCountJournal Property

Gets the stock count journal.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property StockCountJournal As StockCountJournal
    Get
    Private Set
'Usage
Dim instance As SaveStockCountJournalTransactionServiceResponse
Dim value As StockCountJournal

value = instance.StockCountJournal
```

``` csharp
[DataMemberAttribute]
public StockCountJournal StockCountJournal { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property StockCountJournal^ StockCountJournal {
    StockCountJournal^ get ();
    private: void set (StockCountJournal^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.StockCountJournal](stockcountjournal-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [StockCountJournal](stockcountjournal-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[SaveStockCountJournalTransactionServiceResponse Class](savestockcountjournaltransactionserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

