---
title: SalesTransaction.PrepaymentAmountInvoiced Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PrepaymentAmountInvoiced Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.PrepaymentAmountInvoiced
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.salestransaction.prepaymentamountinvoiced(v=AX.60)
ms:contentKeyID: 62214203
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.PrepaymentAmountInvoiced
dev_langs:
- CSharp
- C++
- VB
---

# PrepaymentAmountInvoiced Property

Gets or sets the portion of the prepayment amount that was invoiced (picked up).

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("PREPAYMENTINVOICED")> _
Public Property PrepaymentAmountInvoiced As Decimal
    Get
    Set
'Usage
Dim instance As SalesTransaction
Dim value As Decimal

value = instance.PrepaymentAmountInvoiced

instance.PrepaymentAmountInvoiced = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("PREPAYMENTINVOICED")]
public decimal PrepaymentAmountInvoiced { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"PREPAYMENTINVOICED")]
public:
property Decimal PrepaymentAmountInvoiced {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\)).  

## Remarks

If a customer has paid $100 in form of a deposit and picks up one item that contributes with $20 for the deposit calculation, then the PrepaymentInvoicedAmount is $20.

## See Also

#### Reference

[SalesTransaction Class](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

