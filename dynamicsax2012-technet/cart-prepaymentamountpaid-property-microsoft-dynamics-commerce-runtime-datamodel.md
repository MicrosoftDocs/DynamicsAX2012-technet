---
title: Cart.PrepaymentAmountPaid Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PrepaymentAmountPaid Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart.PrepaymentAmountPaid
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.cart.prepaymentamountpaid(v=AX.60)
ms:contentKeyID: 62209724
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart.PrepaymentAmountPaid
dev_langs:
- CSharp
- C++
- VB
---

# PrepaymentAmountPaid Property

Gets or sets the amount of the prepayment that was paid toward the order (in form of a deposit on order creation).

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ReadOnlyAttribute("PREPAYMENTPAID")> _
<ColumnAttribute("PREPAYMENTPAID")> _
Public Property PrepaymentAmountPaid As Decimal
    Get
    Set
'Usage
Dim instance As Cart
Dim value As Decimal

value = instance.PrepaymentAmountPaid

instance.PrepaymentAmountPaid = value
```

``` csharp
[DataMemberAttribute]
[ReadOnlyAttribute("PREPAYMENTPAID")]
[ColumnAttribute("PREPAYMENTPAID")]
public decimal PrepaymentAmountPaid { get; set; }
```

``` c++
[DataMemberAttribute]
[ReadOnlyAttribute(L"PREPAYMENTPAID")]
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

This is the total amount paid towards the order in previous transactions.

## See Also

#### Reference

[Cart Class](cart-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

