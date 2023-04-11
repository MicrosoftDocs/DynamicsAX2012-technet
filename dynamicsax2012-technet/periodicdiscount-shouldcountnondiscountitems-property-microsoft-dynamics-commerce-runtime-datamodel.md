---
title: PeriodicDiscount.ShouldCountNonDiscountItems Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ShouldCountNonDiscountItems Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PeriodicDiscount.ShouldCountNonDiscountItems
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.periodicdiscount.shouldcountnondiscountitems(v=AX.60)
ms:contentKeyID: 62211607
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PeriodicDiscount.ShouldCountNonDiscountItems
dev_langs:
- CSharp
- C++
- VB
---

# ShouldCountNonDiscountItems Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the threshold offer setting indicated whether non-discount items contribute to threshold amount trigger.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("COUNTNONDISCOUNTITEMS")> _
<DataMemberAttribute> _
Public Property ShouldCountNonDiscountItems As Integer
    Get
    Friend Set
'Usage
Dim instance As PeriodicDiscount
Dim value As Integer

value = instance.ShouldCountNonDiscountItems
```

``` csharp
[ColumnAttribute("COUNTNONDISCOUNTITEMS")]
[DataMemberAttribute]
public int ShouldCountNonDiscountItems { get; internal set; }
```

``` c++
[ColumnAttribute(L"COUNTNONDISCOUNTITEMS")]
[DataMemberAttribute]
public:
property int ShouldCountNonDiscountItems {
    int get ();
    internal: void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[PeriodicDiscount Class](periodicdiscount-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

