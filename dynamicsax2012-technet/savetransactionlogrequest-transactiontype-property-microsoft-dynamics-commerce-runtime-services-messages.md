---
title: SaveTransactionLogRequest.TransactionType Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: TransactionType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SaveTransactionLogRequest.TransactionType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.savetransactionlogrequest.transactiontype(v=AX.60)
ms:contentKeyID: 65321102
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SaveTransactionLogRequest.TransactionType
dev_langs:
- CSharp
- C++
- VB
---

# TransactionType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property TransactionType As TransactionType
    Get
    Private Set
'Usage
Dim instance As SaveTransactionLogRequest
Dim value As TransactionType

value = instance.TransactionType
```

``` csharp
[DataMemberAttribute]
public TransactionType TransactionType { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property TransactionType TransactionType {
    TransactionType get ();
    private: void set (TransactionType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionType](transactiontype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[SaveTransactionLogRequest Class](savetransactionlogrequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

