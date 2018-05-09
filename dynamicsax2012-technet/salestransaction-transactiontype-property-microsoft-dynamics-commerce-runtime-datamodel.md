---
title: SalesTransaction.TransactionType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TransactionType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.TransactionType
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.salestransaction.transactiontype(v=AX.60)
ms:contentKeyID: 62211179
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.TransactionType
dev_langs:
- CSharp
- C++
- VB
---

# TransactionType Property

Gets or sets the transaction type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("TYPE")> _
Public Property TransactionType As SalesTransactionType
    Get
    Set
'Usage
Dim instance As SalesTransaction
Dim value As SalesTransactionType

value = instance.TransactionType

instance.TransactionType = value
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("TYPE")]
public SalesTransactionType TransactionType { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"TYPE")]
public:
property SalesTransactionType TransactionType {
    SalesTransactionType get ();
    void set (SalesTransactionType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransactionType](salestransactiontype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [SalesTransactionType](salestransactiontype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[SalesTransaction Class](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

