---
title: Category.ParentCategory Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ParentCategory Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Category.ParentCategory
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.category.parentcategory(v=AX.60)
ms:contentKeyID: 49844022
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Category.ParentCategory
dev_langs:
- CSharp
- C++
- VB
---

# ParentCategory Property

Gets the paent category.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("PARENTCATEGORY")> _
Public Property ParentCategory As Long
    Get
    Set
'Usage
Dim instance As Category
Dim value As Long

value = instance.ParentCategory

instance.ParentCategory = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("PARENTCATEGORY")]
public long ParentCategory { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"PARENTCATEGORY")]
public:
property long long ParentCategory {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[Category Class](category-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

