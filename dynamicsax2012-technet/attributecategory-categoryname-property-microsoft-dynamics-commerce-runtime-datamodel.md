---
title: AttributeCategory.CategoryName Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CategoryName Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeCategory.CategoryName
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.attributecategory.categoryname(v=AX.60)
ms:contentKeyID: 62213205
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeCategory.CategoryName
dev_langs:
- CSharp
- C++
- VB
---

# CategoryName Property

Gets or sets the name of the category.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("CATEGORYNAME")> _
<DataMemberAttribute> _
Public Property CategoryName As String
    Get
    Set
'Usage
Dim instance As AttributeCategory
Dim value As String

value = instance.CategoryName

instance.CategoryName = value
```

``` csharp
[ColumnAttribute("CATEGORYNAME")]
[DataMemberAttribute]
public string CategoryName { get; set; }
```

``` c++
[ColumnAttribute(L"CATEGORYNAME")]
[DataMemberAttribute]
public:
property String^ CategoryName {
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

