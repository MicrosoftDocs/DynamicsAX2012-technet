---
title: PriceAdjustment.ProductId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ProductId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceAdjustment.ProductId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.priceadjustment.productid(v=AX.60)
ms:contentKeyID: 49855922
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceAdjustment.ProductId
dev_langs:
- CSharp
- C++
- VB
---

# ProductId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the identifier of the product with which this price adjustment is associated.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("PRODUCT")> _
Public Property ProductId As Long
    Get
    Friend Set
'Usage
Dim instance As PriceAdjustment
Dim value As Long

value = instance.ProductId
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("PRODUCT")]
public long ProductId { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"PRODUCT")]
public:
property long long ProductId {
    long long get ();
    internal: void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[PriceAdjustment Class](priceadjustment-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

