---
title: Cart.SubtotalAmount Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SubtotalAmount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart.SubtotalAmount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cart.subtotalamount(v=AX.60)
ms:contentKeyID: 62202101
author: tfehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart.SubtotalAmount
dev_langs:
- CSharp
- C++
- VB
---

# SubtotalAmount Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the subtotal amount on this sales transaction.

Subtotal is the net amount for the transaction (which includes the discounts, but not charges), and optionally the tax amount if tax inclusive.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ReadOnlyAttribute("SUBTOTALAMOUNT")> _
<ColumnAttribute("SUBTOTALAMOUNT")> _
Public Property SubtotalAmount As Decimal
    Get
    Set
'Usage
Dim instance As Cart
Dim value As Decimal

value = instance.SubtotalAmount

instance.SubtotalAmount = value
```

``` csharp
[DataMemberAttribute]
[ReadOnlyAttribute("SUBTOTALAMOUNT")]
[ColumnAttribute("SUBTOTALAMOUNT")]
public decimal SubtotalAmount { get; set; }
```

``` c++
[DataMemberAttribute]
[ReadOnlyAttribute(L"SUBTOTALAMOUNT")]
[ColumnAttribute(L"SUBTOTALAMOUNT")]
public:
property Decimal SubtotalAmount {
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

