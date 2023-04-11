---
title: SalesInvoiceLine.TotalDiscount Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TotalDiscount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesInvoiceLine.TotalDiscount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salesinvoiceline.totaldiscount(v=AX.60)
ms:contentKeyID: 62208334
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesInvoiceLine.TotalDiscount
dev_langs:
- CSharp
- C++
- VB
---

# TotalDiscount Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the total amount deducted by a total amount discounts and total percent discounts on this line.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("TOTALDISCOUNTAMOUNT")> _
<DataMemberAttribute> _
Public Property TotalDiscount As Decimal
    Get
    Set
'Usage
Dim instance As SalesInvoiceLine
Dim value As Decimal

value = instance.TotalDiscount

instance.TotalDiscount = value
```

``` csharp
[ColumnAttribute("TOTALDISCOUNTAMOUNT")]
[DataMemberAttribute]
public decimal TotalDiscount { get; set; }
```

``` c++
[ColumnAttribute(L"TOTALDISCOUNTAMOUNT")]
[DataMemberAttribute]
public:
property Decimal TotalDiscount {
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

