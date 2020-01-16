---
title: RelatedProduct.IsDirectRelation Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsDirectRelation Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.RelatedProduct.IsDirectRelation
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.relatedproduct.isdirectrelation(v=AX.60)
ms:contentKeyID: 62214359
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.RelatedProduct.IsDirectRelation
dev_langs:
- CSharp
- C++
- VB
---

# IsDirectRelation Property

Gets or sets a value indicating whether this is a direct relation.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property IsDirectRelation As Boolean
    Get
    Set
'Usage
Dim instance As RelatedProduct
Dim value As Boolean

value = instance.IsDirectRelation

instance.IsDirectRelation = value
```

``` csharp
[DataMemberAttribute]
public bool IsDirectRelation { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property bool IsDirectRelation {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[RelatedProduct Class](relatedproduct-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

