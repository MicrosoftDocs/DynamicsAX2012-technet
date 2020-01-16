---
title: Item.Product Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Product Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Item.Product
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.item.product(v=AX.60)
ms:contentKeyID: 49843776
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Item.Product
dev_langs:
- CSharp
- C++
- VB
---

# Product Property

Gets the product identifier for this item.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("PRODUCT")> _
Public Property Product As Long
    Get
    Friend Set
'Usage
Dim instance As Item
Dim value As Long

value = instance.Product
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("PRODUCT")]
public long Product { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"PRODUCT")]
public:
property long long Product {
    long long get ();
    internal: void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[Item Class](item-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

