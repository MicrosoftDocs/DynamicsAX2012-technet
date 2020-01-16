---
title: DiscountLine.SaleLineNumber Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SaleLineNumber Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountLine.SaleLineNumber
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.discountline.salelinenumber(v=AX.60)
ms:contentKeyID: 62210789
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountLine.SaleLineNumber
dev_langs:
- CSharp
- C++
- VB
---

# SaleLineNumber Property

Gets or sets the sales line number on which the discount is applied.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("SALELINENUM")> _
<DataMemberAttribute> _
Public Property SaleLineNumber As Decimal
    Get
    Set
'Usage
Dim instance As DiscountLine
Dim value As Decimal

value = instance.SaleLineNumber

instance.SaleLineNumber = value
```

``` csharp
[ColumnAttribute("SALELINENUM")]
[DataMemberAttribute]
public decimal SaleLineNumber { get; set; }
```

``` c++
[ColumnAttribute(L"SALELINENUM")]
[DataMemberAttribute]
public:
property Decimal SaleLineNumber {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[DiscountLine Class](discountline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

