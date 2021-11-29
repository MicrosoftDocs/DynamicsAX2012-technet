---
title: SalesInvoiceLine.PeriodicPercentageDiscount Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PeriodicPercentageDiscount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesInvoiceLine.PeriodicPercentageDiscount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salesinvoiceline.periodicpercentagediscount(v=AX.60)
ms:contentKeyID: 62211037
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesInvoiceLine.PeriodicPercentageDiscount
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
<DataMemberAttribute> _
<ColumnAttribute("PERIODICPERCENTAGEDISCOUNT")> _
Public Property PeriodicPercentageDiscount As Decimal
    Get
    Set
'Usage
Dim instance As SalesInvoiceLine
Dim value As Decimal

value = instance.PeriodicPercentageDiscount

instance.PeriodicPercentageDiscount = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("PERIODICPERCENTAGEDISCOUNT")]
public decimal PeriodicPercentageDiscount { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"PERIODICPERCENTAGEDISCOUNT")]
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

[SalesInvoiceLine Class](salesinvoiceline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

