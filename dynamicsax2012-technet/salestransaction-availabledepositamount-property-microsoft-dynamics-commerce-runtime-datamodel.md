---
title: SalesTransaction.AvailableDepositAmount Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AvailableDepositAmount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.AvailableDepositAmount
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.salestransaction.availabledepositamount(v=AX.60)
ms:contentKeyID: 62210844
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.AvailableDepositAmount
dev_langs:
- CSharp
- C++
- VB
---

# AvailableDepositAmount Property

Gets the amount of the prepayment, paid towards this transaction, that is available (not invoiced \[picked up\] yet), counting as deposit (credit) for the order.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ReadOnlyAttribute("AVAILABLEDEPOSITAMOUNT")> _
<ColumnAttribute("AVAILABLEDEPOSITAMOUNT")> _
Public Property AvailableDepositAmount As Decimal
    Get
    Set
'Usage
Dim instance As SalesTransaction
Dim value As Decimal

value = instance.AvailableDepositAmount

instance.AvailableDepositAmount = value
```

``` csharp
[DataMemberAttribute]
[ReadOnlyAttribute("AVAILABLEDEPOSITAMOUNT")]
[ColumnAttribute("AVAILABLEDEPOSITAMOUNT")]
public decimal AvailableDepositAmount { get; set; }
```

``` c++
[DataMemberAttribute]
[ReadOnlyAttribute(L"AVAILABLEDEPOSITAMOUNT")]
[ColumnAttribute(L"AVAILABLEDEPOSITAMOUNT")]
public:
property Decimal AvailableDepositAmount {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\)).  

## Remarks

If the transaction deposit required is $100 and the client tenders it completely then the DepositAvailableAmount is $100. If two days latter, the client comes to the store and picks one item up whose deposit contribution was, say $20, then the DepositAvailableAmount is $80 now.

## See Also

#### Reference

[SalesTransaction Class](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

