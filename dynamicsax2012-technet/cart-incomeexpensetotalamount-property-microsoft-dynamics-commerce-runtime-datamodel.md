---
title: Cart.IncomeExpenseTotalAmount Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IncomeExpenseTotalAmount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart.IncomeExpenseTotalAmount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cart.incomeexpensetotalamount(v=AX.60)
ms:contentKeyID: 62206883
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart.IncomeExpenseTotalAmount
dev_langs:
- CSharp
- C++
- VB
---

# IncomeExpenseTotalAmount Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the income / expense total amount.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("INCOMEEXPENSEAMOUNT")> _
Public Property IncomeExpenseTotalAmount As Decimal
    Get
    Set
'Usage
Dim instance As Cart
Dim value As Decimal

value = instance.IncomeExpenseTotalAmount

instance.IncomeExpenseTotalAmount = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("INCOMEEXPENSEAMOUNT")]
public decimal IncomeExpenseTotalAmount { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"INCOMEEXPENSEAMOUNT")]
public:
property Decimal IncomeExpenseTotalAmount {
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

