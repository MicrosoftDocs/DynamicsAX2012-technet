---
title: InsertSalesTransactionTablesDataRequest.CustomerOrderTable Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: CustomerOrderTable Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.InsertSalesTransactionTablesDataRequest.CustomerOrderTable
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.insertsalestransactiontablesdatarequest.customerordertable(v=AX.60)
ms:contentKeyID: 65323168
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.InsertSalesTransactionTablesDataRequest.CustomerOrderTable
dev_langs:
- CSharp
- C++
- VB
---

# CustomerOrderTable Property

Gets the customer order table.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Property CustomerOrderTable As DataTable
    Get
    Private Set
'Usage
Dim instance As InsertSalesTransactionTablesDataRequest
Dim value As DataTable

value = instance.CustomerOrderTable
```

``` csharp
public DataTable CustomerOrderTable { get; private set; }
```

``` c++
public:
property DataTable^ CustomerOrderTable {
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

