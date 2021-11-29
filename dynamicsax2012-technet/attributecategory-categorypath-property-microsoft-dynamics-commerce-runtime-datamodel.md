---
title: AttributeCategory.CategoryPath Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CategoryPath Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeCategory.CategoryPath
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.attributecategory.categorypath(v=AX.60)
ms:contentKeyID: 62213094
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeCategory.CategoryPath
dev_langs:
- CSharp
- C++
- VB
---

# CategoryPath Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the category path.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("CATEGORYPATH")> _
<DataMemberAttribute> _
Public Property CategoryPath As String
    Get
    Set
'Usage
Dim instance As AttributeCategory
Dim value As String

value = instance.CategoryPath

instance.CategoryPath = value
```

``` csharp
[ColumnAttribute("CATEGORYPATH")]
[DataMemberAttribute]
public string CategoryPath { get; set; }
```

``` c++
[ColumnAttribute(L"CATEGORYPATH")]
[DataMemberAttribute]
public:
property String^ CategoryPath {
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

