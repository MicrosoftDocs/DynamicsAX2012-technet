---
title: SalesLine.QuantityDiscounted Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: QuantityDiscounted Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.QuantityDiscounted
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salesline.quantitydiscounted(v=AX.60)
ms:contentKeyID: 49820785
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.QuantityDiscounted
dev_langs:
- CSharp
- C++
- VB
---

# QuantityDiscounted Property

Gets or sets how many items have been discounted.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property QuantityDiscounted As Decimal
    Get
    Set
'Usage
Dim instance As SalesLine
Dim value As Decimal

value = instance.QuantityDiscounted

instance.QuantityDiscounted = value
```

``` csharp
[DataMemberAttribute]
public decimal QuantityDiscounted { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Decimal QuantityDiscounted {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## Remarks

Used in calculation of the periodic discount.

## See Also

#### Reference

[SalesLine Class](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

