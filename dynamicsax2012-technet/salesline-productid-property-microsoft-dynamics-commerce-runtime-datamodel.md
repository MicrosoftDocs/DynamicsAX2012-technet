---
title: SalesLine.ProductId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ProductId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.ProductId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salesline.productid(v=AX.60)
ms:contentKeyID: 49856552
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.ProductId
dev_langs:
- CSharp
- C++
- VB
---

# ProductId Property

Gets or sets the primary id of the product from this item.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("LISTINGID")> _
Public Property ProductId As Long
    Get
    Set
'Usage
Dim instance As SalesLine
Dim value As Long

value = instance.ProductId

instance.ProductId = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("LISTINGID")]
public long ProductId { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"LISTINGID")]
public:
property long long ProductId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)).  

## Remarks

This is RecId in EcoResProduct table.

## See Also

#### Reference

[SalesLine Class](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

