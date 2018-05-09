---
title: SalesInvoiceLine.LineDiscount Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LineDiscount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesInvoiceLine.LineDiscount
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.salesinvoiceline.linediscount(v=AX.60)
ms:contentKeyID: 62208467
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesInvoiceLine.LineDiscount
dev_langs:
- CSharp
- C++
- VB
---

# LineDiscount Property

Gets or sets total line discount given in this transaction(excluding the tax).

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("LINEDISCOUNTAMOUNT")> _
Public Property LineDiscount As Decimal
    Get
    Set
'Usage
Dim instance As SalesInvoiceLine
Dim value As Decimal

value = instance.LineDiscount

instance.LineDiscount = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("LINEDISCOUNTAMOUNT")]
public decimal LineDiscount { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"LINEDISCOUNTAMOUNT")]
public:
property Decimal LineDiscount {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[SalesInvoiceLine Class](salesinvoiceline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

