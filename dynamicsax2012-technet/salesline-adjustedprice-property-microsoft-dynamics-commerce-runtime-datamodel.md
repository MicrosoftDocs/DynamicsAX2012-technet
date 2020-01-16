---
title: SalesLine.AdjustedPrice Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AdjustedPrice Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.AdjustedPrice
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salesline.adjustedprice(v=AX.60)
ms:contentKeyID: 62205364
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.AdjustedPrice
dev_langs:
- CSharp
- C++
- VB
---

# AdjustedPrice Property

Gets or sets the price after price adjustments of the item on this sales line.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("ADJUSTMENTPRICE")> _
Public Property AdjustedPrice As Decimal
    Get
    Set
'Usage
Dim instance As SalesLine
Dim value As Decimal

value = instance.AdjustedPrice

instance.AdjustedPrice = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("ADJUSTMENTPRICE")]
public decimal AdjustedPrice { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"ADJUSTMENTPRICE")]
public:
property Decimal AdjustedPrice {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[SalesLine Class](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

