---
title: SalesLine.PeriodicPercentageDiscount Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PeriodicPercentageDiscount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.PeriodicPercentageDiscount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salesline.periodicpercentagediscount(v=AX.60)
ms:contentKeyID: 49854827
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.PeriodicPercentageDiscount
dev_langs:
- CSharp
- C++
- VB
---

# PeriodicPercentageDiscount Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the percentage discount given in this line excluding the total and line discount.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("PERIODICPERCENTAGEDISCOUNT")> _
<DataMemberAttribute> _
Public Property PeriodicPercentageDiscount As Decimal
    Get
    Set
'Usage
Dim instance As SalesLine
Dim value As Decimal

value = instance.PeriodicPercentageDiscount

instance.PeriodicPercentageDiscount = value
```

``` csharp
[ColumnAttribute("PERIODICPERCENTAGEDISCOUNT")]
[DataMemberAttribute]
public decimal PeriodicPercentageDiscount { get; set; }
```

``` c++
[ColumnAttribute(L"PERIODICPERCENTAGEDISCOUNT")]
[DataMemberAttribute]
public:
property Decimal PeriodicPercentageDiscount {
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

