---
title: SaveTransactionLogDataServiceRequest.TransactionLog Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: TransactionLog Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.SaveTransactionLogDataServiceRequest.TransactionLog
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.savetransactionlogdataservicerequest.transactionlog(v=AX.60)
ms:contentKeyID: 65320408
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.SaveTransactionLogDataServiceRequest.TransactionLog
dev_langs:
- CSharp
- C++
- VB
---

# TransactionLog Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the transaction log.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property TransactionLog As TransactionLog
    Get
    Private Set
'Usage
Dim instance As SaveTransactionLogDataServiceRequest
Dim value As TransactionLog

value = instance.TransactionLog
```

``` csharp
[DataMemberAttribute]
public TransactionLog TransactionLog { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property TransactionLog^ TransactionLog {
    TransactionLog^ get ();
    private: void set (TransactionLog^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionLog](transactionlog-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The transaction log.  

## See Also

#### Reference

[SaveTransactionLogDataServiceRequest Class](savetransactionlogdataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

