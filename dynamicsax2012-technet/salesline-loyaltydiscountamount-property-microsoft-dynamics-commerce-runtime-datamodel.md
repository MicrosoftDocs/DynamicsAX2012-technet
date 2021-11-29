---
title: SalesLine.LoyaltyDiscountAmount Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LoyaltyDiscountAmount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.LoyaltyDiscountAmount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salesline.loyaltydiscountamount(v=AX.60)
ms:contentKeyID: 62211368
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.LoyaltyDiscountAmount
dev_langs:
- CSharp
- C++
- VB
---

# LoyaltyDiscountAmount Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the loyalty discount amount given in this line excluding the line and total discounts.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("LOYALTYDISCOUNTAMOUNT")> _
<DataMemberAttribute> _
Public Property LoyaltyDiscountAmount As Decimal
    Get
    Set
'Usage
Dim instance As SalesLine
Dim value As Decimal

value = instance.LoyaltyDiscountAmount

instance.LoyaltyDiscountAmount = value
```

``` csharp
[ColumnAttribute("LOYALTYDISCOUNTAMOUNT")]
[DataMemberAttribute]
public decimal LoyaltyDiscountAmount { get; set; }
```

``` c++
[ColumnAttribute(L"LOYALTYDISCOUNTAMOUNT")]
[DataMemberAttribute]
public:
property Decimal LoyaltyDiscountAmount {
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

