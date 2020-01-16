---
title: DiscountLine.Amount Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Amount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountLine.Amount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.discountline.amount(v=AX.60)
ms:contentKeyID: 49840448
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountLine.Amount
dev_langs:
- CSharp
- C++
- VB
---

# Amount Property

Gets or sets the amount to subtract from the line

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("DISCOUNTAMOUNT")> _
<DataMemberAttribute> _
Public Property Amount As Decimal
    Get
    Set
'Usage
Dim instance As DiscountLine
Dim value As Decimal

value = instance.Amount

instance.Amount = value
```

``` csharp
[ColumnAttribute("DISCOUNTAMOUNT")]
[DataMemberAttribute]
public decimal Amount { get; set; }
```

``` c++
[ColumnAttribute(L"DISCOUNTAMOUNT")]
[DataMemberAttribute]
public:
property Decimal Amount {
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

