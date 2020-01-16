---
title: SalesTransaction.PrepaymentAmountAppliedOnPickup Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PrepaymentAmountAppliedOnPickup Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.PrepaymentAmountAppliedOnPickup
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salestransaction.prepaymentamountappliedonpickup(v=AX.60)
ms:contentKeyID: 62203123
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.PrepaymentAmountAppliedOnPickup
dev_langs:
- CSharp
- C++
- VB
---

# PrepaymentAmountAppliedOnPickup Property

Gets or sets the amount of the prepayment that is to be applied on a pick up at store operation.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("PREPAYMENTAPPLIEDONPICKUP")> _
<ReadOnlyAttribute("PREPAYMENTAPPLIEDONPICKUP")> _
<DataMemberAttribute> _
Public Property PrepaymentAmountAppliedOnPickup As Decimal
    Get
    Set
'Usage
Dim instance As SalesTransaction
Dim value As Decimal

value = instance.PrepaymentAmountAppliedOnPickup

instance.PrepaymentAmountAppliedOnPickup = value
```

``` csharp
[ColumnAttribute("PREPAYMENTAPPLIEDONPICKUP")]
[ReadOnlyAttribute("PREPAYMENTAPPLIEDONPICKUP")]
[DataMemberAttribute]
public decimal PrepaymentAmountAppliedOnPickup { get; set; }
```

``` c++
[ColumnAttribute(L"PREPAYMENTAPPLIEDONPICKUP")]
[ReadOnlyAttribute(L"PREPAYMENTAPPLIEDONPICKUP")]
[DataMemberAttribute]
public:
property Decimal PrepaymentAmountAppliedOnPickup {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## Remarks

When there is a deposit on the order, it counts as credit towards the order. When picking up a product from store, the customer needs to pay whatever that item is worth (price + charges + taxes - discounts, etc). But as the customer has already pre-paid a portion of that item (in the form of a deposit) we need to account for it when calculating the amount due on pick up.

This property represents, on a pick up transaction, how much of the available prepayment can be used as credit when picking up the items.

A CO with $100 deposit, composed of $30 from item A, $20 from item B and $50 from item C. When the customer goes to the store and decides to pick up item A, it needs to pay the amount that A is worth, say $130 total (tax, price, discounts, etc).

However, the customer has already pre-paid $30 of item A in the form of a deposit. Now the customer needs to pay off the difference: $110 (the item worth amount less what he has paid as a deposit).

## See Also

#### Reference

[SalesTransaction Class](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

