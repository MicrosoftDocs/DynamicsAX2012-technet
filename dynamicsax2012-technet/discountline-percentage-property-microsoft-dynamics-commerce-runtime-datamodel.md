---
title: DiscountLine.Percentage Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Percentage Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountLine.Percentage
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.discountline.percentage(v=AX.60)
ms:contentKeyID: 49833808
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountLine.Percentage
dev_langs:
- CSharp
- C++
- VB
---

# Percentage Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the percentage amount to subtract from the line

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("PERCENTAGE")> _
<DataMemberAttribute> _
Public Property Percentage As Decimal
    Get
    Set
'Usage
Dim instance As DiscountLine
Dim value As Decimal

value = instance.Percentage

instance.Percentage = value
```

``` csharp
[ColumnAttribute("PERCENTAGE")]
[DataMemberAttribute]
public decimal Percentage { get; set; }
```

``` c++
[ColumnAttribute(L"PERCENTAGE")]
[DataMemberAttribute]
public:
property Decimal Percentage {
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

