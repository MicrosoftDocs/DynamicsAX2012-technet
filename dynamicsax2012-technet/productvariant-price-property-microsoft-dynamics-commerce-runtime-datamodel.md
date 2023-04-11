---
title: ProductVariant.Price Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Price Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariant.Price
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productvariant.price(v=AX.60)
ms:contentKeyID: 62213544
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariant.Price
dev_langs:
- CSharp
- C++
- VB
---

# Price Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the price after trade agreements have been applied.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Price As Decimal
    Get
    Set
'Usage
Dim instance As ProductVariant
Dim value As Decimal

value = instance.Price

instance.Price = value
```

``` csharp
[DataMemberAttribute]
public decimal Price { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Decimal Price {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[ProductVariant Class](productvariant-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

