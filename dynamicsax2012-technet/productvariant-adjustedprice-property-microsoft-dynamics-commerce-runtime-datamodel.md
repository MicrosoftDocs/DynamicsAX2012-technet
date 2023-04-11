---
title: ProductVariant.AdjustedPrice Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AdjustedPrice Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariant.AdjustedPrice
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productvariant.adjustedprice(v=AX.60)
ms:contentKeyID: 62212122
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariant.AdjustedPrice
dev_langs:
- CSharp
- C++
- VB
---

# AdjustedPrice Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the price after trade agreements and price adjustments have been applied.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property AdjustedPrice As Decimal
    Get
    Set
'Usage
Dim instance As ProductVariant
Dim value As Decimal

value = instance.AdjustedPrice

instance.AdjustedPrice = value
```

``` csharp
[DataMemberAttribute]
public decimal AdjustedPrice { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Decimal AdjustedPrice {
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

