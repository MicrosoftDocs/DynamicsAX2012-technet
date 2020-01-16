---
title: SalesLine.LoyaltyPercentageDiscount Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LoyaltyPercentageDiscount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.LoyaltyPercentageDiscount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salesline.loyaltypercentagediscount(v=AX.60)
ms:contentKeyID: 62209964
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.LoyaltyPercentageDiscount
dev_langs:
- CSharp
- C++
- VB
---

# LoyaltyPercentageDiscount Property

Gets or sets the loyalty discount percentage given in this line excluding the line and total discounts.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("LOYALTYDISCOUNTPERCENTAGE")> _
Public Property LoyaltyPercentageDiscount As Decimal
    Get
    Set
'Usage
Dim instance As SalesLine
Dim value As Decimal

value = instance.LoyaltyPercentageDiscount

instance.LoyaltyPercentageDiscount = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("LOYALTYDISCOUNTPERCENTAGE")]
public decimal LoyaltyPercentageDiscount { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"LOYALTYDISCOUNTPERCENTAGE")]
public:
property Decimal LoyaltyPercentageDiscount {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[SalesLine Class](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

