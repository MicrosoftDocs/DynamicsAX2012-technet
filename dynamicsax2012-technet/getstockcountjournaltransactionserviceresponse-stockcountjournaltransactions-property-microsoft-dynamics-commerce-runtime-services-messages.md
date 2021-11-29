---
title: GetStockCountJournalTransactionServiceResponse.StockCountJournalTransactions Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: StockCountJournalTransactions Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetStockCountJournalTransactionServiceResponse.StockCountJournalTransactions
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getstockcountjournaltransactionserviceresponse.stockcountjournaltransactions(v=AX.60)
ms:contentKeyID: 62211188
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetStockCountJournalTransactionServiceResponse.StockCountJournalTransactions
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
Public Property StockCountJournalTransactions As IEnumerable(Of StockCountJournalTransaction)
    Get
    Private Set
'Usage
Dim instance As GetStockCountJournalTransactionServiceResponse
Dim value As IEnumerable(Of StockCountJournalTransaction)

value = instance.StockCountJournalTransactions
```

``` csharp
[DataMemberAttribute]
public IEnumerable<StockCountJournalTransaction> StockCountJournalTransactions { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property IEnumerable<StockCountJournalTransaction^>^ StockCountJournalTransactions {
    IEnumerable<StockCountJournalTransaction^>^ get ();
    private: void set (IEnumerable<StockCountJournalTransaction^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[StockCountJournalTransaction](stockcountjournaltransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [IEnumerable\<T\>](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[GetStockCountJournalTransactionServiceResponse Class](getstockcountjournaltransactionserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

