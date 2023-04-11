---
title: JoinableTableType Class (Microsoft.Dynamics.Commerce.Runtime.Data.Types)
TOCTitle: JoinableTableType Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Data.Types.JoinableTableType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.types.joinabletabletype(v=AX.60)
ms:contentKeyID: 65322576
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.Types.JoinableTableType
dev_langs:
- CSharp
- C++
- VB
---

# JoinableTableType Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Represents a table type parameter used during set-based operations as a enhanced replacement for the IN (...) syntax.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data.Types](microsoft-dynamics-commerce-runtime-data-types-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Data (in Microsoft.Dynamics.Commerce.Runtime.Data.dll)

## Syntax

``` vb
'Declaration
Public MustInherit Class JoinableTableType _
    Inherits TableType
'Usage
Dim instance As JoinableTableType
```

``` csharp
public abstract class JoinableTableType : TableType
```

``` c++
public ref class JoinableTableType abstract : public TableType
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Data.Types.TableType](tabletype-class-microsoft-dynamics-commerce-runtime-data-types.md)  
    Microsoft.Dynamics.Commerce.Runtime.Data.Types.JoinableTableType  
      [Microsoft.Dynamics.Commerce.Runtime.Data.Types.ItemIdSearchTableType](itemidsearchtabletype-class-microsoft-dynamics-commerce-runtime-data-types.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Data.Types.RecordIdTableType](recordidtabletype-class-microsoft-dynamics-commerce-runtime-data-types.md)  
      [Microsoft.Dynamics.Commerce.Runtime.Data.Types.StringIdTableType](stringidtabletype-class-microsoft-dynamics-commerce-runtime-data-types.md)  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Data.Types Namespace](microsoft-dynamics-commerce-runtime-data-types-namespace.md)

