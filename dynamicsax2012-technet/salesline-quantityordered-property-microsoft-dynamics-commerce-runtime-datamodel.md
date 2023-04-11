---
title: SalesLine.QuantityOrdered Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: QuantityOrdered Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.QuantityOrdered
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salesline.quantityordered(v=AX.60)
ms:contentKeyID: 62207638
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.QuantityOrdered
dev_langs:
- CSharp
- C++
- VB
---

# QuantityOrdered Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the quantity that was ordered for a Customer Order.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("QTYORDERED")> _
<DataMemberAttribute> _
Public Property QuantityOrdered As Nullable(Of Decimal)
    Get
    Set
'Usage
Dim instance As SalesLine
Dim value As Nullable(Of Decimal)

value = instance.QuantityOrdered

instance.QuantityOrdered = value
```

``` csharp
[ColumnAttribute("QTYORDERED")]
[DataMemberAttribute]
public Nullable<decimal> QuantityOrdered { get; set; }
```

``` c++
[ColumnAttribute(L"QTYORDERED")]
[DataMemberAttribute]
public:
property Nullable<Decimal> QuantityOrdered {
    Nullable<Decimal> get ();
    void set (Nullable<Decimal> value);
}
```

#### Property Value

Type: [System.Nullable](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\))\<[Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))\>  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[SalesLine Class](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

