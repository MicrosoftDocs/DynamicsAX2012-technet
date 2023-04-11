---
title: Cart.RequiredDepositAmount Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: RequiredDepositAmount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart.RequiredDepositAmount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cart.requireddepositamount(v=AX.60)
ms:contentKeyID: 62210967
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart.RequiredDepositAmount
dev_langs:
- CSharp
- C++
- VB
---

# RequiredDepositAmount Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the required deposit amount.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("REQUIREDDEPOSIT")> _
<DataMemberAttribute> _
<ReadOnlyAttribute("REQUIREDDEPOSIT")> _
Public Property RequiredDepositAmount As Decimal
    Get
    Set
'Usage
Dim instance As Cart
Dim value As Decimal

value = instance.RequiredDepositAmount

instance.RequiredDepositAmount = value
```

``` csharp
[ColumnAttribute("REQUIREDDEPOSIT")]
[DataMemberAttribute]
[ReadOnlyAttribute("REQUIREDDEPOSIT")]
public decimal RequiredDepositAmount { get; set; }
```

``` c++
[ColumnAttribute(L"REQUIREDDEPOSIT")]
[DataMemberAttribute]
[ReadOnlyAttribute(L"REQUIREDDEPOSIT")]
public:
property Decimal RequiredDepositAmount {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[Cart Class](cart-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

