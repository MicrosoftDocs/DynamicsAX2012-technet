---
title: DiscountLine.EffectiveAmount Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: EffectiveAmount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountLine.EffectiveAmount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.discountline.effectiveamount(v=AX.60)
ms:contentKeyID: 62214898
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountLine.EffectiveAmount
dev_langs:
- CSharp
- C++
- VB
---

# EffectiveAmount Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the effective discount amount (per-unit discount amount \* quantity).

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("AMOUNT")> _
<DataMemberAttribute> _
Public Property EffectiveAmount As Decimal
    Get
    Set
'Usage
Dim instance As DiscountLine
Dim value As Decimal

value = instance.EffectiveAmount

instance.EffectiveAmount = value
```

``` csharp
[ColumnAttribute("AMOUNT")]
[DataMemberAttribute]
public decimal EffectiveAmount { get; set; }
```

``` c++
[ColumnAttribute(L"AMOUNT")]
[DataMemberAttribute]
public:
property Decimal EffectiveAmount {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[DiscountLine Class](discountline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

