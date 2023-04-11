---
title: RetailDiscountLine.DistinctProductVariantId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DistinctProductVariantId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailDiscountLine.DistinctProductVariantId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.retaildiscountline.distinctproductvariantid(v=AX.60)
ms:contentKeyID: 62213696
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailDiscountLine.DistinctProductVariantId
dev_langs:
- CSharp
- C++
- VB
---

# DistinctProductVariantId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the specific product variant ID specified on this discount line.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("VARIANT")> _
Public Property DistinctProductVariantId As Long
    Get
    Set
'Usage
Dim instance As RetailDiscountLine
Dim value As Long

value = instance.DistinctProductVariantId

instance.DistinctProductVariantId = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("VARIANT")]
public long DistinctProductVariantId { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"VARIANT")]
public:
property long long DistinctProductVariantId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[RetailDiscountLine Class](retaildiscountline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

