---
title: SalesInvoiceLine.PeriodicDiscount Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PeriodicDiscount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesInvoiceLine.PeriodicDiscount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salesinvoiceline.periodicdiscount(v=AX.60)
ms:contentKeyID: 62213455
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesInvoiceLine.PeriodicDiscount
dev_langs:
- CSharp
- C++
- VB
---

# PeriodicDiscount Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets total periodic discount given in this line (tax excluded).

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("PERIODICDISCOUNTAMOUNT")> _
<DataMemberAttribute> _
Public Property PeriodicDiscount As Decimal
    Get
    Set
'Usage
Dim instance As SalesInvoiceLine
Dim value As Decimal

value = instance.PeriodicDiscount

instance.PeriodicDiscount = value
```

``` csharp
[ColumnAttribute("PERIODICDISCOUNTAMOUNT")]
[DataMemberAttribute]
public decimal PeriodicDiscount { get; set; }
```

``` c++
[ColumnAttribute(L"PERIODICDISCOUNTAMOUNT")]
[DataMemberAttribute]
public:
property Decimal PeriodicDiscount {
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

