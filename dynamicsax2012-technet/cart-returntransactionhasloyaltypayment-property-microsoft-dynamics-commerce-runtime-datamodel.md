---
title: Cart.ReturnTransactionHasLoyaltyPayment Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ReturnTransactionHasLoyaltyPayment Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart.ReturnTransactionHasLoyaltyPayment
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cart.returntransactionhasloyaltypayment(v=AX.60)
ms:contentKeyID: 62202419
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart.ReturnTransactionHasLoyaltyPayment
dev_langs:
- CSharp
- C++
- VB
---

# ReturnTransactionHasLoyaltyPayment Property

Gets or sets a value indicating whether the original transaction that is being returned has any posted loyalty tender.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ReadOnlyAttribute("RETURNHASLOYALTYPAYMENT")> _
<ColumnAttribute("RETURNHASLOYALTYPAYMENT")> _
Public Property ReturnTransactionHasLoyaltyPayment As Boolean
    Get
    Set
'Usage
Dim instance As Cart
Dim value As Boolean

value = instance.ReturnTransactionHasLoyaltyPayment

instance.ReturnTransactionHasLoyaltyPayment = value
```

``` csharp
[DataMemberAttribute]
[ReadOnlyAttribute("RETURNHASLOYALTYPAYMENT")]
[ColumnAttribute("RETURNHASLOYALTYPAYMENT")]
public bool ReturnTransactionHasLoyaltyPayment { get; set; }
```

``` c++
[DataMemberAttribute]
[ReadOnlyAttribute(L"RETURNHASLOYALTYPAYMENT")]
[ColumnAttribute(L"RETURNHASLOYALTYPAYMENT")]
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

[Cart Class](cart-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

