---
title: Cart.SubtotalAmountWithoutTax Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SubtotalAmountWithoutTax Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart.SubtotalAmountWithoutTax
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cart.subtotalamountwithouttax(v=AX.60)
ms:contentKeyID: 62209323
author: tfehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart.SubtotalAmountWithoutTax
dev_langs:
- CSharp
- C++
- VB
---

# SubtotalAmountWithoutTax Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the subtotal amount on this sales transaction.

Subtotal is the net amount for the transaction (which includes the discounts, but not charges), and excludes tax amount if tax inclusive.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("SUBTOTALAMOUNTWITHOUTTAX")> _
<ReadOnlyAttribute("SUBTOTALAMOUNTWITHOUTTAX")> _
Public Property SubtotalAmountWithoutTax As Decimal
    Get
    Set
'Usage
Dim instance As Cart
Dim value As Decimal

value = instance.SubtotalAmountWithoutTax

instance.SubtotalAmountWithoutTax = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("SUBTOTALAMOUNTWITHOUTTAX")]
[ReadOnlyAttribute("SUBTOTALAMOUNTWITHOUTTAX")]
public decimal SubtotalAmountWithoutTax { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"SUBTOTALAMOUNTWITHOUTTAX")]
[ReadOnlyAttribute(L"SUBTOTALAMOUNTWITHOUTTAX")]
public:
property Decimal SubtotalAmountWithoutTax {
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

