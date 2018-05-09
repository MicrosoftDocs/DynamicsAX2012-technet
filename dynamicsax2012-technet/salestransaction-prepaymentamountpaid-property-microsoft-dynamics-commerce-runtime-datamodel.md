---
title: SalesTransaction.PrepaymentAmountPaid Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PrepaymentAmountPaid Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.PrepaymentAmountPaid
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.salestransaction.prepaymentamountpaid(v=AX.60)
ms:contentKeyID: 62208139
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.PrepaymentAmountPaid
dev_langs:
- CSharp
- C++
- VB
---

# PrepaymentAmountPaid Property

Gets or sets the amount of the deposit that was paid toward the order.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("PREPAYMENTPAID")> _
Public Property PrepaymentAmountPaid As Decimal
    Get
    Set
'Usage
Dim instance As SalesTransaction
Dim value As Decimal

value = instance.PrepaymentAmountPaid

instance.PrepaymentAmountPaid = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("PREPAYMENTPAID")]
public decimal PrepaymentAmountPaid { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"PREPAYMENTPAID")]
public:
property Decimal PrepaymentAmountPaid {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\)).  

## Remarks

This is how much money the customer put into the purchase in form of a deposit.

It will match the required deposit if no deposit override was set and the order is created.

The difference between deposit and prepayment is: Deposit is the amount required for a customer order to be created / edited.

Prepayment is the amount the customer puts into the order to cover the deposit.

The prepayment covers the deposit, but during the CO's life cycle it will match the deposit amount only when the order is (ready to be) created / saved.

## See Also

#### Reference

[SalesTransaction Class](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

