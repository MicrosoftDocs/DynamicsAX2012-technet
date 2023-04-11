---
title: SalesTransaction.ReturnTransactionHasLoyaltyPayment Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ReturnTransactionHasLoyaltyPayment Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.ReturnTransactionHasLoyaltyPayment
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salestransaction.returntransactionhasloyaltypayment(v=AX.60)
ms:contentKeyID: 62210298
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.ReturnTransactionHasLoyaltyPayment
dev_langs:
- CSharp
- C++
- VB
---

# ReturnTransactionHasLoyaltyPayment Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether the original transaction that is being returned has any posted loyalty tender.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("RETURNHASLOYALTYPAYMENT")> _
<DataMemberAttribute> _
<ReadOnlyAttribute("RETURNHASLOYALTYPAYMENT")> _
Public Property ReturnTransactionHasLoyaltyPayment As Boolean
    Get
    Set
'Usage
Dim instance As SalesTransaction
Dim value As Boolean

value = instance.ReturnTransactionHasLoyaltyPayment

instance.ReturnTransactionHasLoyaltyPayment = value
```

``` csharp
[ColumnAttribute("RETURNHASLOYALTYPAYMENT")]
[DataMemberAttribute]
[ReadOnlyAttribute("RETURNHASLOYALTYPAYMENT")]
public bool ReturnTransactionHasLoyaltyPayment { get; set; }
```

``` c++
[ColumnAttribute(L"RETURNHASLOYALTYPAYMENT")]
[DataMemberAttribute]
[ReadOnlyAttribute(L"RETURNHASLOYALTYPAYMENT")]
public:
property bool ReturnTransactionHasLoyaltyPayment {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[SalesTransaction Class](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

