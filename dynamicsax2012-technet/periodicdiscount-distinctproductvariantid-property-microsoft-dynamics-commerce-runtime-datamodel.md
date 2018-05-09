---
title: PeriodicDiscount.DistinctProductVariantId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DistinctProductVariantId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PeriodicDiscount.DistinctProductVariantId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.periodicdiscount.distinctproductvariantid(v=AX.60)
ms:contentKeyID: 62202645
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PeriodicDiscount.DistinctProductVariantId
dev_langs:
- CSharp
- C++
- VB
---

# DistinctProductVariantId Property

Gets or sets the optional distinct variant record Id associated with this retail discount.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("DISTINCTPRODUCTVARIANTID")> _
Public Property DistinctProductVariantId As Long
    Get
    Set
'Usage
Dim instance As PeriodicDiscount
Dim value As Long

value = instance.DistinctProductVariantId

instance.DistinctProductVariantId = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("DISTINCTPRODUCTVARIANTID")]
public long DistinctProductVariantId { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"DISTINCTPRODUCTVARIANTID")]
public:
property long long DistinctProductVariantId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[PeriodicDiscount Class](periodicdiscount-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

