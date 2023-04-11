---
title: Cart.EstimatedShippingAmount Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: EstimatedShippingAmount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart.EstimatedShippingAmount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cart.estimatedshippingamount(v=AX.60)
ms:contentKeyID: 65322351
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart.EstimatedShippingAmount
dev_langs:
- CSharp
- C++
- VB
---

# EstimatedShippingAmount Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("ESTIMATEDSHIPPINGAMOUNT")> _
Public Property EstimatedShippingAmount As Nullable(Of Decimal)
    Get
    Set
'Usage
Dim instance As Cart
Dim value As Nullable(Of Decimal)

value = instance.EstimatedShippingAmount

instance.EstimatedShippingAmount = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("ESTIMATEDSHIPPINGAMOUNT")]
public Nullable<decimal> EstimatedShippingAmount { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"ESTIMATEDSHIPPINGAMOUNT")]
public:
property Nullable<Decimal> EstimatedShippingAmount {
    Nullable<Decimal> get ();
    void set (Nullable<Decimal> value);
}
```

#### Property Value

Type: [System.Nullable](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\))\<[Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))\>  

## See Also

#### Reference

[Cart Class](cart-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

