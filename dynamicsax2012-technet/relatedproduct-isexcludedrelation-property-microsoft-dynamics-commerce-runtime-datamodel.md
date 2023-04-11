---
title: RelatedProduct.IsExcludedRelation Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsExcludedRelation Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.RelatedProduct.IsExcludedRelation
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.relatedproduct.isexcludedrelation(v=AX.60)
ms:contentKeyID: 62210497
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.RelatedProduct.IsExcludedRelation
dev_langs:
- CSharp
- C++
- VB
---

# IsExcludedRelation Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether this is relation is excluded.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("EXCLUSION")> _
<DataMemberAttribute> _
Public Property IsExcludedRelation As Boolean
    Get
    Set
'Usage
Dim instance As RelatedProduct
Dim value As Boolean

value = instance.IsExcludedRelation

instance.IsExcludedRelation = value
```

``` csharp
[ColumnAttribute("EXCLUSION")]
[DataMemberAttribute]
public bool IsExcludedRelation { get; set; }
```

``` c++
[ColumnAttribute(L"EXCLUSION")]
[DataMemberAttribute]
public:
property bool IsExcludedRelation {
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

