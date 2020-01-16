---
title: NumberSequenceSeedTypeHelper.GetReceiptTransactionType Method (TransactionType, Decimal, CustomerOrderMode) (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: GetReceiptTransactionType Method (TransactionType, Decimal, CustomerOrderMode)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.NumberSequenceSeedTypeHelper.GetReceiptTransactionType(Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionType,System.Decimal,Microsoft.Dynamics.Commerce.Runtime.DataModel.CustomerOrderMode)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.numbersequenceseedtypehelper.getreceipttransactiontype(v=AX.60)
ms:contentKeyID: 65322513
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetReceiptTransactionType Method (TransactionType, Decimal, CustomerOrderMode)

Gets receipt transaction type from transaction type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GetReceiptTransactionType ( _
    transactionType As TransactionType, _
    netAmountWithNoTax As Decimal, _
    customerOrderMode As CustomerOrderMode _
) As ReceiptTransactionType
'Usage
Dim transactionType As TransactionType
Dim netAmountWithNoTax As Decimal
Dim customerOrderMode As CustomerOrderMode
Dim returnValue As ReceiptTransactionType

returnValue = NumberSequenceSeedTypeHelper.GetReceiptTransactionType(transactionType, _
    netAmountWithNoTax, customerOrderMode)
```

``` csharp
public static ReceiptTransactionType GetReceiptTransactionType(
    TransactionType transactionType,
    decimal netAmountWithNoTax,
    CustomerOrderMode customerOrderMode
)
```

``` c++
public:
static ReceiptTransactionType GetReceiptTransactionType(
    TransactionType transactionType, 
    Decimal netAmountWithNoTax, 
    CustomerOrderMode customerOrderMode
)
```

#### Parameters

  - transactionType  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionType](transactiontype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - netAmountWithNoTax  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - customerOrderMode  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CustomerOrderMode](customerordermode-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptTransactionType](receipttransactiontype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
The receipt transaction type.  

## See Also

#### Reference

[NumberSequenceSeedTypeHelper Class](numbersequenceseedtypehelper-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[GetReceiptTransactionType Overload](numbersequenceseedtypehelper-getreceipttransactiontype-method-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

