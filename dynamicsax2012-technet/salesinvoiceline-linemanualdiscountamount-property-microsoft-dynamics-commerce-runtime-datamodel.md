---
title: SalesInvoiceLine.LineManualDiscountAmount Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LineManualDiscountAmount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesInvoiceLine.LineManualDiscountAmount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salesinvoiceline.linemanualdiscountamount(v=AX.60)
ms:contentKeyID: 62203941
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesInvoiceLine.LineManualDiscountAmount
dev_langs:
- CSharp
- C++
- VB
---

# LineManualDiscountAmount Property

Gets or sets the manual line amount off value.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("LINEMANUALDISCOUNTAMOUNT")> _
<DataMemberAttribute> _
Public Property LineManualDiscountAmount As Decimal
    Get
    Set
'Usage
Dim instance As SalesInvoiceLine
Dim value As Decimal

value = instance.LineManualDiscountAmount

instance.LineManualDiscountAmount = value
```

``` csharp
[ColumnAttribute("LINEMANUALDISCOUNTAMOUNT")]
[DataMemberAttribute]
public decimal LineManualDiscountAmount { get; set; }
```

``` c++
[ColumnAttribute(L"LINEMANUALDISCOUNTAMOUNT")]
[DataMemberAttribute]
public:
property Decimal LineManualDiscountAmount {
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

