---
title: TransactionServiceClient.ParseTransactions Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: ParseTransactions Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.ParseTransactions(System.Xml.Linq.XElement)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.transactionserviceclient.parsetransactions(v=AX.60)
ms:contentKeyID: 62214295
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.ParseTransactions
dev_langs:
- CSharp
- C++
- VB
---

# ParseTransactions Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Parse xml StockCount journal transaction data into object.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Shared Function ParseTransactions ( _
    xmlJournalTransaction As XElement _
) As StockCountJournalTransaction
'Usage
Dim xmlJournalTransaction As XElement
Dim returnValue As StockCountJournalTransaction

returnValue = TransactionServiceClient.ParseTransactions(xmlJournalTransaction)
```

``` csharp
public static StockCountJournalTransaction ParseTransactions(
    XElement xmlJournalTransaction
)
```

``` c++
public:
static StockCountJournalTransaction^ ParseTransactions(
    XElement^ xmlJournalTransaction
)
```

#### Parameters

  - xmlJournalTransaction  
    Type: [System.Xml.Linq.XElement](https://technet.microsoft.com/library/bb340098\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.StockCountJournalTransaction](stockcountjournaltransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns the StockCountJournalTransactions object.  

## See Also

#### Reference

[TransactionServiceClient Class](transactionserviceclient-class-microsoft-dynamics-commerce-runtime-transactionservice.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService Namespace](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)

