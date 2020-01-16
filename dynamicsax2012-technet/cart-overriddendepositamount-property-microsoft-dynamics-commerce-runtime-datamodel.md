---
title: Cart.OverriddenDepositAmount Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: OverriddenDepositAmount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart.OverriddenDepositAmount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cart.overriddendepositamount(v=AX.60)
ms:contentKeyID: 62207631
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart.OverriddenDepositAmount
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
<ColumnAttribute("DEPOSITOVERRIDE")> _
<DataMemberAttribute> _
Public Property OverriddenDepositAmount As Nullable(Of Decimal)
    Get
    Set
'Usage
Dim instance As Cart
Dim value As Nullable(Of Decimal)

value = instance.OverriddenDepositAmount

instance.OverriddenDepositAmount = value
```

``` csharp
[ColumnAttribute("DEPOSITOVERRIDE")]
[DataMemberAttribute]
public Nullable<decimal> OverriddenDepositAmount { get; set; }
```

``` c++
[ColumnAttribute(L"DEPOSITOVERRIDE")]
[DataMemberAttribute]
public:
property Nullable<Decimal> OverriddenDepositAmount {
    Nullable<Decimal> get ();
    void set (Nullable<Decimal> value);
}
```

#### Property Value

Type: [System.Nullable](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\))\<[Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))\>  
Returns [Nullable\<T\>](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\)).  

## See Also

#### Reference

[Cart Class](cart-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

