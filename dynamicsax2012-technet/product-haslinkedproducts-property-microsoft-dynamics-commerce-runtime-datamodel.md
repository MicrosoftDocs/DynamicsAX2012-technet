---
title: Product.HasLinkedProducts Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: HasLinkedProducts Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Product.HasLinkedProducts
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.product.haslinkedproducts(v=AX.60)
ms:contentKeyID: 62206858
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Product.HasLinkedProducts
dev_langs:
- CSharp
- C++
- VB
---

# HasLinkedProducts Property

Gets a value indicating whether the product has linked products.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property HasLinkedProducts As Boolean
    Get
    Friend Set
'Usage
Dim instance As Product
Dim value As Boolean

value = instance.HasLinkedProducts
```

``` csharp
[DataMemberAttribute]
public bool HasLinkedProducts { get; internal set; }
```

``` c++
[DataMemberAttribute]
public:
property bool HasLinkedProducts {
    bool get ();
    internal: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[Product Class](product-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

