---
title: SalesLine.TotalPercentageDiscount Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TotalPercentageDiscount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.TotalPercentageDiscount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salesline.totalpercentagediscount(v=AX.60)
ms:contentKeyID: 49837932
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.TotalPercentageDiscount
dev_langs:
- CSharp
- C++
- VB
---

# TotalPercentageDiscount Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the percentage discount given in this line excluding the linediscount.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("TOTALDISCOUNTPERCENTAGE")> _
<DataMemberAttribute> _
Public Property TotalPercentageDiscount As Decimal
    Get
    Set
'Usage
Dim instance As SalesLine
Dim value As Decimal

value = instance.TotalPercentageDiscount

instance.TotalPercentageDiscount = value
```

``` csharp
[ColumnAttribute("TOTALDISCOUNTPERCENTAGE")]
[DataMemberAttribute]
public decimal TotalPercentageDiscount { get; set; }
```

``` c++
[ColumnAttribute(L"TOTALDISCOUNTPERCENTAGE")]
[DataMemberAttribute]
public:
property Decimal TotalPercentageDiscount {
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

