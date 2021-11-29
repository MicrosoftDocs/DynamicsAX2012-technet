---
title: RetailCategoryMember.CategoryId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CategoryId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailCategoryMember.CategoryId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.retailcategorymember.categoryid(v=AX.60)
ms:contentKeyID: 62203732
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailCategoryMember.CategoryId
dev_langs:
- CSharp
- C++
- VB
---

# CategoryId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the category ID specified on this discount line.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("CATEGORY")> _
<DataMemberAttribute> _
Public Property CategoryId As Long
    Get
    Set
'Usage
Dim instance As RetailCategoryMember
Dim value As Long

value = instance.CategoryId

instance.CategoryId = value
```

``` csharp
[ColumnAttribute("CATEGORY")]
[DataMemberAttribute]
public long CategoryId { get; set; }
```

``` c++
[ColumnAttribute(L"CATEGORY")]
[DataMemberAttribute]
public:
property long long CategoryId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[RetailCategoryMember Class](retailcategorymember-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

