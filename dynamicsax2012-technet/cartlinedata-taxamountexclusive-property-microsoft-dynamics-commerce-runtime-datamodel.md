---
title: CartLineData.TaxAmountExclusive Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TaxAmountExclusive Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLineData.TaxAmountExclusive
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cartlinedata.taxamountexclusive(v=AX.60)
ms:contentKeyID: 49841042
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLineData.TaxAmountExclusive
dev_langs:
- CSharp
- C++
- VB
---

# TaxAmountExclusive Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the total tax amount (exclusive only) on this sales line.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("TAXAMOUNTEXCLUSIVE")> _
Public Property TaxAmountExclusive As Decimal
    Get
    Friend Set
'Usage
Dim instance As CartLineData
Dim value As Decimal

value = instance.TaxAmountExclusive
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("TAXAMOUNTEXCLUSIVE")]
public decimal TaxAmountExclusive { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"TAXAMOUNTEXCLUSIVE")]
public:
property Decimal TaxAmountExclusive {
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

