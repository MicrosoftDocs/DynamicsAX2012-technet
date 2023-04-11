---
title: TransactionServiceClient.ToXml Method (StockCountJournal) (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: ToXml Method (StockCountJournal)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.ToXml(Microsoft.Dynamics.Commerce.Runtime.DataModel.StockCountJournal)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.transactionserviceclient.toxml(v=AX.60)
ms:contentKeyID: 62206261
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# ToXml Method (StockCountJournal)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Serialize to xml format of a stock count journal.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Shared Function ToXml ( _
    journal As StockCountJournal _
) As String
'Usage
Dim journal As StockCountJournal
Dim returnValue As String

returnValue = TransactionServiceClient.ToXml(journal)
```

``` csharp
public static string ToXml(
    StockCountJournal journal
)
```

``` c++
public:
static String^ ToXml(
    StockCountJournal^ journal
)
```

#### Parameters

  - journal  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.StockCountJournal](stockcountjournal-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Xml format of a stock count journal.  

## See Also

#### Reference

[TransactionServiceClient Class](transactionserviceclient-class-microsoft-dynamics-commerce-runtime-transactionservice.md)

[ToXml Overload](transactionserviceclient-toxml-method-microsoft-dynamics-commerce-runtime-transactionservice.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService Namespace](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)

