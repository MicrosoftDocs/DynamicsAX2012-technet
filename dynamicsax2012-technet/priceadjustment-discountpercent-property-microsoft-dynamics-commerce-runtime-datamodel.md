---
title: PriceAdjustment.DiscountPercent Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DiscountPercent Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceAdjustment.DiscountPercent
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.priceadjustment.discountpercent(v=AX.60)
ms:contentKeyID: 49833894
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceAdjustment.DiscountPercent
dev_langs:
- CSharp
- C++
- VB
---

# DiscountPercent Property

Gets the percent off amount for "Percent off" method.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("DISCPCT")> _
Public Property DiscountPercent As Decimal
    Get
    Friend Set
'Usage
Dim instance As PriceAdjustment
Dim value As Decimal

value = instance.DiscountPercent
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("DISCPCT")]
public decimal DiscountPercent { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"DISCPCT")]
public:
property Decimal DiscountPercent {
    Decimal get ();
    internal: void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[PriceAdjustment Class](priceadjustment-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

