---
title: RelatedProduct.RelationName Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: RelationName Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.RelatedProduct.RelationName
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.relatedproduct.relationname(v=AX.60)
ms:contentKeyID: 62211499
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.RelatedProduct.RelationName
dev_langs:
- CSharp
- C++
- VB
---

# RelationName Property

Gets or sets the name of the relation.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("PRODUCTRELATIONTYPE")> _
Public Property RelationName As String
    Get
    Set
'Usage
Dim instance As RelatedProduct
Dim value As String

value = instance.RelationName

instance.RelationName = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("PRODUCTRELATIONTYPE")]
public string RelationName { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"PRODUCTRELATIONTYPE")]
public:
property String^ RelationName {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[RelatedProduct Class](relatedproduct-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

