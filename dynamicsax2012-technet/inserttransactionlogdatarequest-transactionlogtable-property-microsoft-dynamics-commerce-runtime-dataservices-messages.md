---
title: InsertTransactionLogDataRequest.TransactionLogTable Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: TransactionLogTable Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.InsertTransactionLogDataRequest.TransactionLogTable
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.inserttransactionlogdatarequest.transactionlogtable(v=AX.60)
ms:contentKeyID: 65315985
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.InsertTransactionLogDataRequest.TransactionLogTable
dev_langs:
- CSharp
- C++
- VB
---

# TransactionLogTable Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the transaction table.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property TransactionLogTable As DataTable
    Get
    Private Set
'Usage
Dim instance As InsertTransactionLogDataRequest
Dim value As DataTable

value = instance.TransactionLogTable
```

``` csharp
[DataMemberAttribute]
public DataTable TransactionLogTable { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property DataTable^ TransactionLogTable {
    DataTable^ get ();
    private: void set (DataTable^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataTable](datatable-class-microsoft-dynamics-commerce-runtime-data-types.md)  
Returns [DataTable](datatable-class-microsoft-dynamics-commerce-runtime-data-types.md).  

## See Also

#### Reference

[InsertTransactionLogDataRequest Class](inserttransactionlogdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

