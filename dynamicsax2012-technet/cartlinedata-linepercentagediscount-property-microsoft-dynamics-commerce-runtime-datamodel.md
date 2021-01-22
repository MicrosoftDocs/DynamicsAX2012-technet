---
title: CartLineData.LinePercentageDiscount Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LinePercentageDiscount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLineData.LinePercentageDiscount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cartlinedata.linepercentagediscount(v=AX.60)
ms:contentKeyID: 62207759
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLineData.LinePercentageDiscount
dev_langs:
- CSharp
- C++
- VB
---

# LinePercentageDiscount Property

Gets or sets the percentage discount given in this line excluding the total discount.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("LINEPERCENTAGEDISCOUNT")> _
<DataMemberAttribute> _
Public Property LinePercentageDiscount As Decimal
    Get
    Set
'Usage
Dim instance As CartLineData
Dim value As Decimal

value = instance.LinePercentageDiscount

instance.LinePercentageDiscount = value
```

``` csharp
[ColumnAttribute("LINEPERCENTAGEDISCOUNT")]
[DataMemberAttribute]
public decimal LinePercentageDiscount { get; set; }
```

``` c++
[ColumnAttribute(L"LINEPERCENTAGEDISCOUNT")]
[DataMemberAttribute]
public:
property Decimal LinePercentageDiscount {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[CartLineData Class](cartlinedata-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

