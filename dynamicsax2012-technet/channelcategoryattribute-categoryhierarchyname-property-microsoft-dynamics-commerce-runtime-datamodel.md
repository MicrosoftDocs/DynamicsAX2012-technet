---
title: ChannelCategoryAttribute.CategoryHierarchyName Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CategoryHierarchyName Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelCategoryAttribute.CategoryHierarchyName
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.channelcategoryattribute.categoryhierarchyname(v=AX.60)
ms:contentKeyID: 65320949
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelCategoryAttribute.CategoryHierarchyName
dev_langs:
- CSharp
- C++
- VB
---

# CategoryHierarchyName Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the category hierarchy name.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("CATEGORYHIERARCHYNAME")> _
Public Property CategoryHierarchyName As String
    Get
    Friend Set
'Usage
Dim instance As ChannelCategoryAttribute
Dim value As String

value = instance.CategoryHierarchyName
```

``` csharp
[ColumnAttribute("CATEGORYHIERARCHYNAME")]
public string CategoryHierarchyName { get; internal set; }
```

``` c++
[ColumnAttribute(L"CATEGORYHIERARCHYNAME")]
public:
property String^ CategoryHierarchyName {
    String^ get ();
    internal: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ChannelCategoryAttribute Class](channelcategoryattribute-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

