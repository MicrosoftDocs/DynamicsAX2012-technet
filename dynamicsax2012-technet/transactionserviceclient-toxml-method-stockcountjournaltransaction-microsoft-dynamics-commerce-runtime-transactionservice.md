---
title: TransactionServiceClient.ToXml Method (StockCountJournalTransaction) (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: ToXml Method (StockCountJournalTransaction)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.ToXml(Microsoft.Dynamics.Commerce.Runtime.DataModel.StockCountJournalTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.transactionserviceclient.toxml(v=AX.60)
ms:contentKeyID: 62210403
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# ToXml Method (StockCountJournalTransaction)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Serialize to xml format of a SC journal transaction.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Shared Function ToXml ( _
    journalTransaction As StockCountJournalTransaction _
) As String
'Usage
Dim journalTransaction As StockCountJournalTransaction
Dim returnValue As String

returnValue = TransactionServiceClient.ToXml(journalTransaction)
```

``` csharp
public static string ToXml(
    StockCountJournalTransaction journalTransaction
)
```

``` c++
public:
static String^ ToXml(
    StockCountJournalTransaction^ journalTransaction
)
```

#### Parameters

  - journalTransaction  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.StockCountJournalTransaction](stockcountjournaltransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Xml format of a SC journal transaction.  

## See Also

#### Reference

[TransactionServiceClient Class](transactionserviceclient-class-microsoft-dynamics-commerce-runtime-transactionservice.md)

[ToXml Overload](transactionserviceclient-toxml-method-microsoft-dynamics-commerce-runtime-transactionservice.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService Namespace](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)

