---
title: PeriodicDiscount.MixAndMatchDiscountAmount Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: MixAndMatchDiscountAmount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PeriodicDiscount.MixAndMatchDiscountAmount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.periodicdiscount.mixandmatchdiscountamount(v=AX.60)
ms:contentKeyID: 49840993
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PeriodicDiscount.MixAndMatchDiscountAmount
dev_langs:
- CSharp
- C++
- VB
---

# MixAndMatchDiscountAmount Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the amount off of a mix and match set if this is a mix and match discount.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("DISCOUNTAMOUNTVALUE")> _
Public Property MixAndMatchDiscountAmount As Decimal
    Get
    Friend Set
'Usage
Dim instance As PeriodicDiscount
Dim value As Decimal

value = instance.MixAndMatchDiscountAmount
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("DISCOUNTAMOUNTVALUE")]
public decimal MixAndMatchDiscountAmount { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"DISCOUNTAMOUNTVALUE")]
public:
property Decimal MixAndMatchDiscountAmount {
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

