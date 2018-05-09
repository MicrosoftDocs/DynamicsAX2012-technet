---
title: CartLine.QuantityOrdered Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: QuantityOrdered Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLine.QuantityOrdered
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.cartline.quantityordered(v=AX.60)
ms:contentKeyID: 62212625
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLine.QuantityOrdered
dev_langs:
- CSharp
- C++
- VB
---

# QuantityOrdered Property

Gets or sets the QuantityOrdered for the cartline (customer order).

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property QuantityOrdered As Nullable(Of Decimal)
    Get
    Set
'Usage
Dim instance As CartLine
Dim value As Nullable(Of Decimal)

value = instance.QuantityOrdered

instance.QuantityOrdered = value
```

``` csharp
[DataMemberAttribute]
public Nullable<decimal> QuantityOrdered { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Nullable<Decimal> QuantityOrdered {
    Nullable<Decimal> get ();
    void set (Nullable<Decimal> value);
}
```

#### Property Value

Type: [System.Nullable](https://technet.microsoft.com/en-us/library/b3h38hb0\(v=ax.60\))\<[Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))\>  
Returns [Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[CartLine Class](cartline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

