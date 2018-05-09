---
title: ProductCategoryAssociation.CategoryRecordId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CategoryRecordId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductCategoryAssociation.CategoryRecordId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.productcategoryassociation.categoryrecordid(v=AX.60)
ms:contentKeyID: 62204949
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductCategoryAssociation.CategoryRecordId
dev_langs:
- CSharp
- C++
- VB
---

# CategoryRecordId Property

Gets the associated category record identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("CATEGORY")> _
Public Property CategoryRecordId As Long
    Get
    Friend Set
'Usage
Dim instance As ProductCategoryAssociation
Dim value As Long

value = instance.CategoryRecordId
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("CATEGORY")]
public long CategoryRecordId { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"CATEGORY")]
public:
property long long CategoryRecordId {
    long long get ();
    internal: void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[ProductCategoryAssociation Class](productcategoryassociation-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

