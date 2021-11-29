---
title: SalesInvoiceLine.DiscountPercent Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DiscountPercent Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesInvoiceLine.DiscountPercent
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salesinvoiceline.discountpercent(v=AX.60)
ms:contentKeyID: 62202380
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesInvoiceLine.DiscountPercent
dev_langs:
- CSharp
- C++
- VB
---

# DiscountPercent Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the discount percent.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("DISCPERCENT")> _
Public Property DiscountPercent As Decimal
    Get
    Set
'Usage
Dim instance As SalesInvoiceLine
Dim value As Decimal

value = instance.DiscountPercent

instance.DiscountPercent = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("DISCPERCENT")]
public decimal DiscountPercent { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"DISCPERCENT")]
public:
property Decimal DiscountPercent {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
The discount percent.  

## See Also

#### Reference

[SalesInvoiceLine Class](salesinvoiceline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

