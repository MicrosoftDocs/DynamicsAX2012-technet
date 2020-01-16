---
title: AttributeCategory.CategoryHierarchyName Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CategoryHierarchyName Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeCategory.CategoryHierarchyName
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.attributecategory.categoryhierarchyname(v=AX.60)
ms:contentKeyID: 62209296
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeCategory.CategoryHierarchyName
dev_langs:
- CSharp
- C++
- VB
---

# CategoryHierarchyName Property

Gets or sets the name of the category hierarchy.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("CATEGORYHIERARCHYNAME")> _
<DataMemberAttribute> _
Public Property CategoryHierarchyName As String
    Get
    Set
'Usage
Dim instance As AttributeCategory
Dim value As String

value = instance.CategoryHierarchyName

instance.CategoryHierarchyName = value
```

``` csharp
[ColumnAttribute("CATEGORYHIERARCHYNAME")]
[DataMemberAttribute]
public string CategoryHierarchyName { get; set; }
```

``` c++
[ColumnAttribute(L"CATEGORYHIERARCHYNAME")]
[DataMemberAttribute]
public:
property String^ CategoryHierarchyName {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[AttributeCategory Class](attributecategory-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

