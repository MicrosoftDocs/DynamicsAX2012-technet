---
title: InsertSalesTransactionTablesDataRequest.TransactionTable Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: TransactionTable Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.InsertSalesTransactionTablesDataRequest.TransactionTable
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.insertsalestransactiontablesdatarequest.transactiontable(v=AX.60)
ms:contentKeyID: 65315996
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.InsertSalesTransactionTablesDataRequest.TransactionTable
dev_langs:
- CSharp
- C++
- VB
---

# TransactionTable Property

Gets the transaction table.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Property TransactionTable As DataTable
    Get
    Private Set
'Usage
Dim instance As InsertSalesTransactionTablesDataRequest
Dim value As DataTable

value = instance.TransactionTable
```

``` csharp
public DataTable TransactionTable { get; private set; }
```

``` c++
public:
property DataTable^ TransactionTable {
    DataTable^ get ();
    private: void set (DataTable^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataTable](datatable-class-microsoft-dynamics-commerce-runtime-data-types.md)  
Returns [DataTable](datatable-class-microsoft-dynamics-commerce-runtime-data-types.md).  

## See Also

#### Reference

[InsertSalesTransactionTablesDataRequest Class](insertsalestransactiontablesdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

