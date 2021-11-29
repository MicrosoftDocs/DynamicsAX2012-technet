---
title: PeriodicDiscount.DiscountLinePercentOrValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DiscountLinePercentOrValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PeriodicDiscount.DiscountLinePercentOrValue
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.periodicdiscount.discountlinepercentorvalue(v=AX.60)
ms:contentKeyID: 49839113
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PeriodicDiscount.DiscountLinePercentOrValue
dev_langs:
- CSharp
- C++
- VB
---

# DiscountLinePercentOrValue Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the percent or amount value from the discount line.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("DISCOUNTPERCENTORVALUE")> _
Public Property DiscountLinePercentOrValue As Decimal
    Get
    Friend Set
'Usage
Dim instance As PeriodicDiscount
Dim value As Decimal

value = instance.DiscountLinePercentOrValue
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("DISCOUNTPERCENTORVALUE")]
public decimal DiscountLinePercentOrValue { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"DISCOUNTPERCENTORVALUE")]
public:
property Decimal DiscountLinePercentOrValue {
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

