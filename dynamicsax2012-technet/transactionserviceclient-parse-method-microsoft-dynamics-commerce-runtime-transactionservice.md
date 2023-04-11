---
title: TransactionServiceClient.Parse Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: Parse Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.Parse(System.Xml.Linq.XElement)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.transactionserviceclient.parse(v=AX.60)
ms:contentKeyID: 62214080
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.Parse
dev_langs:
- CSharp
- C++
- VB
---

# Parse Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Parse StockCount journal xml data into object.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Shared Function Parse ( _
    xmlJournal As XElement _
) As StockCountJournal
'Usage
Dim xmlJournal As XElement
Dim returnValue As StockCountJournal

returnValue = TransactionServiceClient.Parse(xmlJournal)
```

``` csharp
public static StockCountJournal Parse(
    XElement xmlJournal
)
```

``` c++
public:
static StockCountJournal^ Parse(
    XElement^ xmlJournal
)
```

#### Parameters

  - xmlJournal  
    Type: [System.Xml.Linq.XElement](https://technet.microsoft.com/library/bb340098\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.StockCountJournal](stockcountjournal-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns the StockCountJournal object.  

## See Also

#### Reference

[TransactionServiceClient Class](transactionserviceclient-class-microsoft-dynamics-commerce-runtime-transactionservice.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService Namespace](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)

