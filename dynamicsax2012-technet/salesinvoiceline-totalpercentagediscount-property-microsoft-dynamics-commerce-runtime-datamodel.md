---
title: SalesInvoiceLine.TotalPercentageDiscount Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TotalPercentageDiscount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesInvoiceLine.TotalPercentageDiscount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salesinvoiceline.totalpercentagediscount(v=AX.60)
ms:contentKeyID: 62205701
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesInvoiceLine.TotalPercentageDiscount
dev_langs:
- CSharp
- C++
- VB
---

# TotalPercentageDiscount Property

Gets or sets the percentage discount given in this line excluding the linediscount.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("TOTALDISCOUNTPERCENTAGE")> _
Public Property TotalPercentageDiscount As Decimal
    Get
    Set
'Usage
Dim instance As SalesInvoiceLine
Dim value As Decimal

value = instance.TotalPercentageDiscount

instance.TotalPercentageDiscount = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("TOTALDISCOUNTPERCENTAGE")]
public decimal TotalPercentageDiscount { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"TOTALDISCOUNTPERCENTAGE")]
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

[SalesInvoiceLine Class](salesinvoiceline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

