---
title: PeriodicDiscount.DiscountLineNumber Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DiscountLineNumber Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PeriodicDiscount.DiscountLineNumber
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.periodicdiscount.discountlinenumber(v=AX.60)
ms:contentKeyID: 49850295
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PeriodicDiscount.DiscountLineNumber
dev_langs:
- CSharp
- C++
- VB
---

# DiscountLineNumber Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the identifier of the discount line for this rule.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("LINENUM")> _
<DataMemberAttribute> _
Public Property DiscountLineNumber As Decimal
    Get
    Friend Set
'Usage
Dim instance As PeriodicDiscount
Dim value As Decimal

value = instance.DiscountLineNumber
```

``` csharp
[ColumnAttribute("LINENUM")]
[DataMemberAttribute]
public decimal DiscountLineNumber { get; internal set; }
```

``` c++
[ColumnAttribute(L"LINENUM")]
[DataMemberAttribute]
public:
property Decimal DiscountLineNumber {
    Decimal get ();
    internal: void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[PeriodicDiscount Class](periodicdiscount-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

