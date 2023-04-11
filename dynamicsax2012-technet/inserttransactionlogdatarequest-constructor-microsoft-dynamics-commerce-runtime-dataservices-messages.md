---
title: InsertTransactionLogDataRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: InsertTransactionLogDataRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.InsertTransactionLogDataRequest.#ctor(System.Int64,Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataTable)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.inserttransactionlogdatarequest.inserttransactionlogdatarequest(v=AX.60)
ms:contentKeyID: 65320348
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.InsertTransactionLogDataRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# InsertTransactionLogDataRequest Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [InsertTransactionLogDataRequest](inserttransactionlogdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    channelId As Long, _
    transactionLogTable As DataTable _
)
'Usage
Dim channelId As Long
Dim transactionLogTable As DataTable

Dim instance As New InsertTransactionLogDataRequest(channelId, _
    transactionLogTable)
```

``` csharp
public InsertTransactionLogDataRequest(
    long channelId,
    DataTable transactionLogTable
)
```

``` c++
public:
InsertTransactionLogDataRequest(
    long long channelId, 
    DataTable^ transactionLogTable
)
```

#### Parameters

  - channelId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - transactionLogTable  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataTable](datatable-class-microsoft-dynamics-commerce-runtime-data-types.md)  

## See Also

#### Reference

[InsertTransactionLogDataRequest Class](inserttransactionlogdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

