---
title: SyncStockCountTransactionsFromAxServiceResponse.StockCountJournalTransactions Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: StockCountJournalTransactions Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SyncStockCountTransactionsFromAxServiceResponse.StockCountJournalTransactions
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.syncstockcounttransactionsfromaxserviceresponse.stockcountjournaltransactions(v=AX.60)
ms:contentKeyID: 62211095
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SyncStockCountTransactionsFromAxServiceResponse.StockCountJournalTransactions
dev_langs:
- CSharp
- C++
- VB
---

# StockCountJournalTransactions Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the collection of stock count journal transactions.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property StockCountJournalTransactions As ReadOnlyCollection(Of StockCountJournalTransaction)
    Get
    Private Set
'Usage
Dim instance As SyncStockCountTransactionsFromAxServiceResponse
Dim value As ReadOnlyCollection(Of StockCountJournalTransaction)

value = instance.StockCountJournalTransactions
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<StockCountJournalTransaction> StockCountJournalTransactions { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<StockCountJournalTransaction^>^ StockCountJournalTransactions {
    ReadOnlyCollection<StockCountJournalTransaction^>^ get ();
    private: void set (ReadOnlyCollection<StockCountJournalTransaction^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[StockCountJournalTransaction](stockcountjournaltransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[SyncStockCountTransactionsFromAxServiceResponse Class](syncstockcounttransactionsfromaxserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

