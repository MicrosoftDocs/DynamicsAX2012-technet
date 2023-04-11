---
title: OrgUnit.IsPublished Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsPublished Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.OrgUnit.IsPublished
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.orgunit.ispublished(v=AX.60)
ms:contentKeyID: 65317399
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.OrgUnit.IsPublished
dev_langs:
- CSharp
- C++
- VB
---

# IsPublished Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("ISPUBLISHED")> _
<IgnoreDataMemberAttribute> _
Public ReadOnly Property IsPublished As Boolean
    Get
'Usage
Dim instance As OrgUnit
Dim value As Boolean

value = instance.IsPublished
```

``` csharp
[ColumnAttribute("ISPUBLISHED")]
[IgnoreDataMemberAttribute]
public bool IsPublished { get; }
```

``` c++
[ColumnAttribute(L"ISPUBLISHED")]
[IgnoreDataMemberAttribute]
public:
property bool IsPublished {
    bool get ();
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[OrgUnit Class](orgunit-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

