---
title: CartLine.QuantityInvoiced Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: QuantityInvoiced Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLine.QuantityInvoiced
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cartline.quantityinvoiced(v=AX.60)
ms:contentKeyID: 62210258
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLine.QuantityInvoiced
dev_langs:
- CSharp
- C++
- VB
---

# QuantityInvoiced Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the quantity previously invoiced for the cartline (customer order).

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property QuantityInvoiced As Nullable(Of Decimal)
    Get
    Set
'Usage
Dim instance As CartLine
Dim value As Nullable(Of Decimal)

value = instance.QuantityInvoiced

instance.QuantityInvoiced = value
```

``` csharp
[DataMemberAttribute]
public Nullable<decimal> QuantityInvoiced { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Nullable<Decimal> QuantityInvoiced {
    Nullable<Decimal> get ();
    void set (Nullable<Decimal> value);
}
```

#### Property Value

Type: [System.Nullable](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\))\<[Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))\>  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[CartLine Class](cartline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

