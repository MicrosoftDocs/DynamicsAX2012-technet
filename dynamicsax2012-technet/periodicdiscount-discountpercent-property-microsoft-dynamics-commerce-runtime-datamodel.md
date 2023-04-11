---
title: PeriodicDiscount.DiscountPercent Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DiscountPercent Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PeriodicDiscount.DiscountPercent
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.periodicdiscount.discountpercent(v=AX.60)
ms:contentKeyID: 49843059
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PeriodicDiscount.DiscountPercent
dev_langs:
- CSharp
- C++
- VB
---

# DiscountPercent Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the percent off amount if this is a discount offer rule.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("DISCPCT")> _
<DataMemberAttribute> _
Public Property DiscountPercent As Decimal
    Get
    Friend Set
'Usage
Dim instance As PeriodicDiscount
Dim value As Decimal

value = instance.DiscountPercent
```

``` csharp
[ColumnAttribute("DISCPCT")]
[DataMemberAttribute]
public decimal DiscountPercent { get; internal set; }
```

``` c++
[ColumnAttribute(L"DISCPCT")]
[DataMemberAttribute]
public:
property Decimal DiscountPercent {
    Decimal get ();
    internal: void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[PeriodicDiscount Class](periodicdiscount-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

