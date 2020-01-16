---
title: SaveTransactionLogRequest Constructor (TransactionType, String) (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: SaveTransactionLogRequest Constructor (TransactionType, String)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SaveTransactionLogRequest.#ctor(Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionType,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.savetransactionlogrequest.savetransactionlogrequest(v=AX.60)
ms:contentKeyID: 65321538
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# SaveTransactionLogRequest Constructor (TransactionType, String)

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    transactionType As TransactionType, _
    transactionId As String _
)
'Usage
Dim transactionType As TransactionType
Dim transactionId As String

Dim instance As New SaveTransactionLogRequest(transactionType, _
    transactionId)
```

``` csharp
public SaveTransactionLogRequest(
    TransactionType transactionType,
    string transactionId
)
```

``` c++
public:
SaveTransactionLogRequest(
    TransactionType transactionType, 
    String^ transactionId
)
```

#### Parameters

  - transactionType  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionType](transactiontype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - transactionId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[SaveTransactionLogRequest Class](savetransactionlogrequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[SaveTransactionLogRequest Overload](savetransactionlogrequest-constructor-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

