---
title: Product.IndexedProductSchema Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IndexedProductSchema Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Product.IndexedProductSchema
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.product.indexedproductschema(v=AX.60)
ms:contentKeyID: 62207785
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Product.IndexedProductSchema
dev_langs:
- CSharp
- C++
- VB
---

# IndexedProductSchema Property

Gets the names of the properties for which this product has values.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Property IndexedProductSchema As ProductPropertySchema
    Get
    Friend Set
'Usage
Dim instance As Product
Dim value As ProductPropertySchema

value = instance.IndexedProductSchema
```

``` csharp
[IgnoreDataMemberAttribute]
public ProductPropertySchema IndexedProductSchema { get; internal set; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property ProductPropertySchema^ IndexedProductSchema {
    ProductPropertySchema^ get ();
    internal: void set (ProductPropertySchema^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductPropertySchema](productpropertyschema-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [ProductPropertySchema](productpropertyschema-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[Product Class](product-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

