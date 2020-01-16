---
title: CartLineData.DiscountAmount Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DiscountAmount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLineData.DiscountAmount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cartlinedata.discountamount(v=AX.60)
ms:contentKeyID: 49833488
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLineData.DiscountAmount
dev_langs:
- CSharp
- C++
- VB
---

# DiscountAmount Property

Gets the discount amount on this sales line.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("DISCOUNTAMOUNT")> _
Public Property DiscountAmount As Decimal
    Get
    Friend Set
'Usage
Dim instance As CartLineData
Dim value As Decimal

value = instance.DiscountAmount
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("DISCOUNTAMOUNT")]
public decimal DiscountAmount { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"DISCOUNTAMOUNT")]
public:
property Decimal DiscountAmount {
    Decimal get ();
    internal: void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[CartLineData Class](cartlinedata-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

