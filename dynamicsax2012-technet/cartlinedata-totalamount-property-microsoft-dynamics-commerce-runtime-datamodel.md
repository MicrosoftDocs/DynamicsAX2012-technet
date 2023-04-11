---
title: CartLineData.TotalAmount Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TotalAmount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLineData.TotalAmount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cartlinedata.totalamount(v=AX.60)
ms:contentKeyID: 49845731
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLineData.TotalAmount
dev_langs:
- CSharp
- C++
- VB
---

# TotalAmount Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the total amount on this sales transaction.Total amount includes taxes, prices, discounts, but no charges.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("TOTALAMOUNT")> _
Public Property TotalAmount As Decimal
    Get
    Set
'Usage
Dim instance As CartLineData
Dim value As Decimal

value = instance.TotalAmount

instance.TotalAmount = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("TOTALAMOUNT")]
public decimal TotalAmount { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"TOTALAMOUNT")]
public:
property Decimal TotalAmount {
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

