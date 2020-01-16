---
title: RetailDiscountLine.DiscountLineNumber Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DiscountLineNumber Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailDiscountLine.DiscountLineNumber
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.retaildiscountline.discountlinenumber(v=AX.60)
ms:contentKeyID: 62208644
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailDiscountLine.DiscountLineNumber
dev_langs:
- CSharp
- C++
- VB
---

# DiscountLineNumber Property

Gets or sets the identifier of the discount line for this rule.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("LINENUM")> _
<DataMemberAttribute> _
Public Property DiscountLineNumber As Decimal
    Get
    Set
'Usage
Dim instance As RetailDiscountLine
Dim value As Decimal

value = instance.DiscountLineNumber

instance.DiscountLineNumber = value
```

``` csharp
[ColumnAttribute("LINENUM")]
[DataMemberAttribute]
public decimal DiscountLineNumber { get; set; }
```

``` c++
[ColumnAttribute(L"LINENUM")]
[DataMemberAttribute]
public:
property Decimal DiscountLineNumber {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[RetailDiscountLine Class](retaildiscountline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

