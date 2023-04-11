---
title: PeriodicDiscount.ProductId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ProductId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PeriodicDiscount.ProductId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.periodicdiscount.productid(v=AX.60)
ms:contentKeyID: 62206529
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PeriodicDiscount.ProductId
dev_langs:
- CSharp
- C++
- VB
---

# ProductId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the product record Id associated with this retail discount.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("PRODUCTID")> _
Public Property ProductId As Long
    Get
    Set
'Usage
Dim instance As PeriodicDiscount
Dim value As Long

value = instance.ProductId

instance.ProductId = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("PRODUCTID")]
public long ProductId { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"PRODUCTID")]
public:
property long long ProductId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[PeriodicDiscount Class](periodicdiscount-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

