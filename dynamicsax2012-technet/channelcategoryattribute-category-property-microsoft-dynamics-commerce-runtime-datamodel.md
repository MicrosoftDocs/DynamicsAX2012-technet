---
title: ChannelCategoryAttribute.Category Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Category Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelCategoryAttribute.Category
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.channelcategoryattribute.category(v=AX.60)
ms:contentKeyID: 65323150
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelCategoryAttribute.Category
dev_langs:
- CSharp
- C++
- VB
---

# Category Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the channel category identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("CATEGORY")> _
Public ReadOnly Property Category As Long
    Get
'Usage
Dim instance As ChannelCategoryAttribute
Dim value As Long

value = instance.Category
```

``` csharp
[ColumnAttribute("CATEGORY")]
public long Category { get; }
```

``` c++
[ColumnAttribute(L"CATEGORY")]
public:
property long long Category {
    long long get ();
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[ChannelCategoryAttribute Class](channelcategoryattribute-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

