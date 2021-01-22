---
title: Cart.TaxAmount Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TaxAmount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart.TaxAmount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cart.taxamount(v=AX.60)
ms:contentKeyID: 49837495
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart.TaxAmount
dev_langs:
- CSharp
- C++
- VB
---

# TaxAmount Property

Gets or sets the tax amount on this sales transaction.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("TAXAMOUNT")> _
Public Property TaxAmount As Decimal
    Get
    Set
'Usage
Dim instance As Cart
Dim value As Decimal

value = instance.TaxAmount

instance.TaxAmount = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("TAXAMOUNT")]
public decimal TaxAmount { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"TAXAMOUNT")]
public:
property Decimal TaxAmount {
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

