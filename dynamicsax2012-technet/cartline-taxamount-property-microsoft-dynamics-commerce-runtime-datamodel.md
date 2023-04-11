---
title: CartLine.TaxAmount Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TaxAmount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLine.TaxAmount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cartline.taxamount(v=AX.60)
ms:contentKeyID: 62204131
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLine.TaxAmount
dev_langs:
- CSharp
- C++
- VB
---

# TaxAmount Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the total tax amount on this sales line.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property TaxAmount As Decimal
    Get
    Set
'Usage
Dim instance As CartLine
Dim value As Decimal

value = instance.TaxAmount

instance.TaxAmount = value
```

``` csharp
[DataMemberAttribute]
public decimal TaxAmount { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Decimal TaxAmount {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[CartLine Class](cartline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

