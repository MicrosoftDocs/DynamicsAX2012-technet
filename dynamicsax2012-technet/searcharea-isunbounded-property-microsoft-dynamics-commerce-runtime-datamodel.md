---
title: SearchArea.IsUnbounded Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsUnbounded Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SearchArea.IsUnbounded
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.searcharea.isunbounded(v=AX.60)
ms:contentKeyID: 62205758
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SearchArea.IsUnbounded
dev_langs:
- CSharp
- C++
- VB
---

# IsUnbounded Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a value indicating whether an unbounded search space has been set.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property IsUnbounded As Boolean
    Get
    Private Set
'Usage
Dim instance As SearchArea
Dim value As Boolean

value = instance.IsUnbounded
```

``` csharp
[DataMemberAttribute]
public bool IsUnbounded { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property bool IsUnbounded {
    bool get ();
    private: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
If true the search area is unbounded; otherwise, false.  

## See Also

#### Reference

[SearchArea Class](searcharea-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

