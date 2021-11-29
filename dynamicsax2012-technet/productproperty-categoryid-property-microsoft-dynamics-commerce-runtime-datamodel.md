---
title: ProductProperty.CategoryId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CategoryId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductProperty.CategoryId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productproperty.categoryid(v=AX.60)
ms:contentKeyID: 65321360
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductProperty.CategoryId
dev_langs:
- CSharp
- C++
- VB
---

# CategoryId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("CATEGORY")> _
Public Property CategoryId As Long
    Get
    Friend Set
'Usage
Dim instance As ProductProperty
Dim value As Long

value = instance.CategoryId
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("CATEGORY")]
public long CategoryId { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"CATEGORY")]
public:
property long long CategoryId {
    long long get ();
    internal: void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

## See Also

#### Reference

[ProductProperty Class](productproperty-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

