---
title: AttributeCategory.Category Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Category Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeCategory.Category
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.attributecategory.category(v=AX.60)
ms:contentKeyID: 49852825
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeCategory.Category
dev_langs:
- CSharp
- C++
- VB
---

# Category Property

Gets or sets the record identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("CATEGORY")> _
<DataMemberAttribute> _
Public Property Category As Long
    Get
    Set
'Usage
Dim instance As AttributeCategory
Dim value As Long

value = instance.Category

instance.Category = value
```

``` csharp
[ColumnAttribute("CATEGORY")]
[DataMemberAttribute]
public long Category { get; set; }
```

``` c++
[ColumnAttribute(L"CATEGORY")]
[DataMemberAttribute]
public:
property long long Category {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
The record identifier.  

## See Also

#### Reference

[AttributeCategory Class](attributecategory-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

