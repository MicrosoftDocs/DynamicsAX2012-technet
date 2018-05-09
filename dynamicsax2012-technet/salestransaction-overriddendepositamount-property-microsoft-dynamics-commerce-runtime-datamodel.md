---
title: SalesTransaction.OverriddenDepositAmount Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: OverriddenDepositAmount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.OverriddenDepositAmount
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.salestransaction.overriddendepositamount(v=AX.60)
ms:contentKeyID: 62212841
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.OverriddenDepositAmount
dev_langs:
- CSharp
- C++
- VB
---

# OverriddenDepositAmount Property

Gets or sets the deposit override amount for the transaction.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("DEPOSITOVERRIDE")> _
Public Property OverriddenDepositAmount As Nullable(Of Decimal)
    Get
    Set
'Usage
Dim instance As SalesTransaction
Dim value As Nullable(Of Decimal)

value = instance.OverriddenDepositAmount

instance.OverriddenDepositAmount = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("DEPOSITOVERRIDE")]
public Nullable<decimal> OverriddenDepositAmount { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"DEPOSITOVERRIDE")]
public:
property Nullable<Decimal> OverriddenDepositAmount {
    Nullable<Decimal> get ();
    void set (Nullable<Decimal> value);
}
```

#### Property Value

Type: [System.Nullable](https://technet.microsoft.com/en-us/library/b3h38hb0\(v=ax.60\))\<[Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))\>  
Returns [Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[SalesTransaction Class](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

