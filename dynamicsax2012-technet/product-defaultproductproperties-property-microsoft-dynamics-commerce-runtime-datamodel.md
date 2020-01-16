---
title: Product.DefaultProductProperties Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DefaultProductProperties Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Product.DefaultProductProperties
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.product.defaultproductproperties(v=AX.60)
ms:contentKeyID: 65321669
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Product.DefaultProductProperties
dev_langs:
- CSharp
- C++
- VB
---

# DefaultProductProperties Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property DefaultProductProperties As ProductPropertyDictionary
    Get
    Friend Set
'Usage
Dim instance As Product
Dim value As ProductPropertyDictionary

value = instance.DefaultProductProperties
```

``` csharp
[DataMemberAttribute]
public ProductPropertyDictionary DefaultProductProperties { get; internal set; }
```

``` c++
[DataMemberAttribute]
public:
property ProductPropertyDictionary^ DefaultProductProperties {
    ProductPropertyDictionary^ get ();
    internal: void set (ProductPropertyDictionary^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductPropertyDictionary](productpropertydictionary-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[Product Class](product-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

