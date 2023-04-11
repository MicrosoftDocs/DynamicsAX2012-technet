---
title: DiscountLine.DealPrice Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DealPrice Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountLine.DealPrice
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.discountline.dealprice(v=AX.60)
ms:contentKeyID: 62204396
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountLine.DealPrice
dev_langs:
- CSharp
- C++
- VB
---

# DealPrice Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the amount to subtract from the line.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("DEALPRICE")> _
Public Property DealPrice As Decimal
    Get
    Set
'Usage
Dim instance As DiscountLine
Dim value As Decimal

value = instance.DealPrice

instance.DealPrice = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("DEALPRICE")]
public decimal DealPrice { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"DEALPRICE")]
public:
property Decimal DealPrice {
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

