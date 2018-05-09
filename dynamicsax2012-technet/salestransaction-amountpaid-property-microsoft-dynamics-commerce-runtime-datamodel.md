---
title: SalesTransaction.AmountPaid Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AmountPaid Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.AmountPaid
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.salestransaction.amountpaid(v=AX.60)
ms:contentKeyID: 62203938
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.AmountPaid
dev_langs:
- CSharp
- C++
- VB
---

# AmountPaid Property

Gets or sets the amount paid.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("AMOUNTPAID")> _
Public Property AmountPaid As Decimal
    Get
    Set
'Usage
Dim instance As SalesTransaction
Dim value As Decimal

value = instance.AmountPaid

instance.AmountPaid = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("AMOUNTPAID")]
public decimal AmountPaid { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"AMOUNTPAID")]
public:
property Decimal AmountPaid {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\)).  

## Remarks

This represents the amount that is already tendered for the transaction.

## See Also

#### Reference

[SalesTransaction Class](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

