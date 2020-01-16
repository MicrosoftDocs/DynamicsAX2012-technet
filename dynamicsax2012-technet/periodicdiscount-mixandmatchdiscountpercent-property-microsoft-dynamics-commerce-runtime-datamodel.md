---
title: PeriodicDiscount.MixAndMatchDiscountPercent Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: MixAndMatchDiscountPercent Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PeriodicDiscount.MixAndMatchDiscountPercent
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.periodicdiscount.mixandmatchdiscountpercent(v=AX.60)
ms:contentKeyID: 49850733
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PeriodicDiscount.MixAndMatchDiscountPercent
dev_langs:
- CSharp
- C++
- VB
---

# MixAndMatchDiscountPercent Property

Gets the percent off of a mix and match set if this is a mix and match discount.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("DISCOUNTPERCENTVALUE")> _
<DataMemberAttribute> _
Public Property MixAndMatchDiscountPercent As Decimal
    Get
    Friend Set
'Usage
Dim instance As PeriodicDiscount
Dim value As Decimal

value = instance.MixAndMatchDiscountPercent
```

``` csharp
[ColumnAttribute("DISCOUNTPERCENTVALUE")]
[DataMemberAttribute]
public decimal MixAndMatchDiscountPercent { get; internal set; }
```

``` c++
[ColumnAttribute(L"DISCOUNTPERCENTVALUE")]
[DataMemberAttribute]
public:
property Decimal MixAndMatchDiscountPercent {
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

