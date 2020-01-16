---
title: JoinableTableType.TableTypeJoinColumn Property  (Microsoft.Dynamics.Commerce.Runtime.Data.Types)
TOCTitle: TableTypeJoinColumn Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.Types.JoinableTableType.TableTypeJoinColumn
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.types.joinabletabletype.tabletypejoincolumn(v=AX.60)
ms:contentKeyID: 65320100
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.Types.JoinableTableType.TableTypeJoinColumn
dev_langs:
- CSharp
- C++
- VB
---

# TableTypeJoinColumn Property

Gets the join column name of the table value parameter.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data.Types](microsoft-dynamics-commerce-runtime-data-types-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Data (in Microsoft.Dynamics.Commerce.Runtime.Data.dll)

## Syntax

``` vb
'Declaration
Public MustOverride ReadOnly Property TableTypeJoinColumn As String
    Get
'Usage
Dim instance As JoinableTableType
Dim value As String

value = instance.TableTypeJoinColumn
```

``` csharp
public abstract string TableTypeJoinColumn { get; }
```

``` c++
public:
virtual property String^ TableTypeJoinColumn {
    String^ get () abstract;
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[JoinableTableType Class](joinabletabletype-class-microsoft-dynamics-commerce-runtime-data-types.md)

[Microsoft.Dynamics.Commerce.Runtime.Data.Types Namespace](microsoft-dynamics-commerce-runtime-data-types-namespace.md)

