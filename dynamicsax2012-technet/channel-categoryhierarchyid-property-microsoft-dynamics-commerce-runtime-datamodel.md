---
title: Channel.CategoryHierarchyId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CategoryHierarchyId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Channel.CategoryHierarchyId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.channel.categoryhierarchyid(v=AX.60)
ms:contentKeyID: 49830298
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Channel.CategoryHierarchyId
dev_langs:
- CSharp
- C++
- VB
---

# CategoryHierarchyId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the category hierarchy identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("CATEGORYHIERARCHYID")> _
Public Property CategoryHierarchyId As Long
    Get
    Friend Set
'Usage
Dim instance As Channel
Dim value As Long

value = instance.CategoryHierarchyId
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("CATEGORYHIERARCHYID")]
public long CategoryHierarchyId { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"CATEGORYHIERARCHYID")]
public:
property long long CategoryHierarchyId {
    long long get ();
    internal: void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[Channel Class](channel-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

