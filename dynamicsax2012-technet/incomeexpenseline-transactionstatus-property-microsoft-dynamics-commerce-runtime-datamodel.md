---
title: IncomeExpenseLine.TransactionStatus Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TransactionStatus Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.IncomeExpenseLine.TransactionStatus
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.incomeexpenseline.transactionstatus(v=AX.60)
ms:contentKeyID: 62208534
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.IncomeExpenseLine.TransactionStatus
dev_langs:
- CSharp
- C++
- VB
---

# TransactionStatus Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the transaction status.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("TRANSACTIONSTATUS")> _
Public Property TransactionStatus As TransactionStatus
    Get
    Set
'Usage
Dim instance As IncomeExpenseLine
Dim value As TransactionStatus

value = instance.TransactionStatus

instance.TransactionStatus = value
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("TRANSACTIONSTATUS")]
public TransactionStatus TransactionStatus { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"TRANSACTIONSTATUS")]
public:
property TransactionStatus TransactionStatus {
    TransactionStatus get ();
    void set (TransactionStatus value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionStatus](transactionstatus-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [TransactionStatus](transactionstatus-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[IncomeExpenseLine Class](incomeexpenseline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

