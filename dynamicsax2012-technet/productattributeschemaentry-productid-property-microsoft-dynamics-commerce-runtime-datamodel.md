---
title: ProductAttributeSchemaEntry.ProductId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ProductId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductAttributeSchemaEntry.ProductId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productattributeschemaentry.productid(v=AX.60)
ms:contentKeyID: 65316207
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductAttributeSchemaEntry.ProductId
dev_langs:
- CSharp
- C++
- VB
---

# ProductId Property

Gets or sets the associated category record identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("PRODUCT")> _
<DataMemberAttribute> _
Public Property ProductId As Long
    Get
    Set
'Usage
Dim instance As ProductAttributeSchemaEntry
Dim value As Long

value = instance.ProductId

instance.ProductId = value
```

``` csharp
[ColumnAttribute("PRODUCT")]
[DataMemberAttribute]
public long ProductId { get; set; }
```

``` c++
[ColumnAttribute(L"PRODUCT")]
[DataMemberAttribute]
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

[ProductAttributeSchemaEntry Class](productattributeschemaentry-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

