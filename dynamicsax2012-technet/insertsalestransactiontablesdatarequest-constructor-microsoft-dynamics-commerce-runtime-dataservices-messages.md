---
title: InsertSalesTransactionTablesDataRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: InsertSalesTransactionTablesDataRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.InsertSalesTransactionTablesDataRequest.#ctor(Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataTable,Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataTable,Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataTable,Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataTable,Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataTable,Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataTable,Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataTable,Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataTable,Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataTable,Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataTable,Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataTable,Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataTable,Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataTable,Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataTable,Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataTable)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.insertsalestransactiontablesdatarequest.insertsalestransactiontablesdatarequest(v=AX.60)
ms:contentKeyID: 65320508
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.InsertSalesTransactionTablesDataRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# InsertSalesTransactionTablesDataRequest Constructor

Initializes a new instance of the [InsertSalesTransactionTablesDataRequest](insertsalestransactiontablesdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    transactionTable As DataTable, _
    markupTable As DataTable, _
    taxTable As DataTable, _
    paymentTable As DataTable, _
    linesTable As DataTable, _
    incomeExpenseTable As DataTable, _
    attributeTable As DataTable, _
    addressTable As DataTable, _
    discountTable As DataTable, _
    reasonCodeTable As DataTable, _
    propertiesTable As DataTable, _
    rewardPointTable As DataTable, _
    affiliationsTable As DataTable, _
    customerOrderTable As DataTable, _
    invoiceTable As DataTable _
)
'Usage
Dim transactionTable As DataTable
Dim markupTable As DataTable
Dim taxTable As DataTable
Dim paymentTable As DataTable
Dim linesTable As DataTable
Dim incomeExpenseTable As DataTable
Dim attributeTable As DataTable
Dim addressTable As DataTable
Dim discountTable As DataTable
Dim reasonCodeTable As DataTable
Dim propertiesTable As DataTable
Dim rewardPointTable As DataTable
Dim affiliationsTable As DataTable
Dim customerOrderTable As DataTable
Dim invoiceTable As DataTable

Dim instance As New InsertSalesTransactionTablesDataRequest(transactionTable, _
    markupTable, taxTable, paymentTable, _
    linesTable, incomeExpenseTable, _
    attributeTable, addressTable, discountTable, _
    reasonCodeTable, propertiesTable, _
    rewardPointTable, affiliationsTable, _
    customerOrderTable, invoiceTable)
```

``` csharp
public InsertSalesTransactionTablesDataRequest(
    DataTable transactionTable,
    DataTable markupTable,
    DataTable taxTable,
    DataTable paymentTable,
    DataTable linesTable,
    DataTable incomeExpenseTable,
    DataTable attributeTable,
    DataTable addressTable,
    DataTable discountTable,
    DataTable reasonCodeTable,
    DataTable propertiesTable,
    DataTable rewardPointTable,
    DataTable affiliationsTable,
    DataTable customerOrderTable,
    DataTable invoiceTable
)
```

``` c++
public:
InsertSalesTransactionTablesDataRequest(
    DataTable^ transactionTable, 
    DataTable^ markupTable, 
    DataTable^ taxTable, 
    DataTable^ paymentTable, 
    DataTable^ linesTable, 
    DataTable^ incomeExpenseTable, 
    DataTable^ attributeTable, 
    DataTable^ addressTable, 
    DataTable^ discountTable, 
    DataTable^ reasonCodeTable, 
    DataTable^ propertiesTable, 
    DataTable^ rewardPointTable, 
    DataTable^ affiliationsTable, 
    DataTable^ customerOrderTable, 
    DataTable^ invoiceTable
)
```

#### Parameters

  - transactionTable  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataTable](datatable-class-microsoft-dynamics-commerce-runtime-data-types.md)  

<!-- end list -->

  - markupTable  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataTable](datatable-class-microsoft-dynamics-commerce-runtime-data-types.md)  

<!-- end list -->

  - taxTable  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataTable](datatable-class-microsoft-dynamics-commerce-runtime-data-types.md)  

<!-- end list -->

  - paymentTable  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataTable](datatable-class-microsoft-dynamics-commerce-runtime-data-types.md)  

<!-- end list -->

  - linesTable  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataTable](datatable-class-microsoft-dynamics-commerce-runtime-data-types.md)  

<!-- end list -->

  - incomeExpenseTable  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataTable](datatable-class-microsoft-dynamics-commerce-runtime-data-types.md)  

<!-- end list -->

  - attributeTable  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataTable](datatable-class-microsoft-dynamics-commerce-runtime-data-types.md)  

<!-- end list -->

  - addressTable  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataTable](datatable-class-microsoft-dynamics-commerce-runtime-data-types.md)  

<!-- end list -->

  - discountTable  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataTable](datatable-class-microsoft-dynamics-commerce-runtime-data-types.md)  

<!-- end list -->

  - reasonCodeTable  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataTable](datatable-class-microsoft-dynamics-commerce-runtime-data-types.md)  

<!-- end list -->

  - propertiesTable  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataTable](datatable-class-microsoft-dynamics-commerce-runtime-data-types.md)  

<!-- end list -->

  - rewardPointTable  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataTable](datatable-class-microsoft-dynamics-commerce-runtime-data-types.md)  

<!-- end list -->

  - affiliationsTable  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataTable](datatable-class-microsoft-dynamics-commerce-runtime-data-types.md)  

<!-- end list -->

  - customerOrderTable  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataTable](datatable-class-microsoft-dynamics-commerce-runtime-data-types.md)  

<!-- end list -->

  - invoiceTable  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataTable](datatable-class-microsoft-dynamics-commerce-runtime-data-types.md)  

## See Also

#### Reference

[InsertSalesTransactionTablesDataRequest Class](insertsalestransactiontablesdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

