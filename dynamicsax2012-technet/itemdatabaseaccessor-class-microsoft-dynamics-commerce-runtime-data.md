---
title: ItemDatabaseAccessor Class (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: ItemDatabaseAccessor Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Data.ItemDatabaseAccessor
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.itemdatabaseaccessor(v=AX.60)
ms:contentKeyID: 62205923
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ItemDatabaseAccessor
dev_langs:
- CSharp
- C++
- VB
---

# ItemDatabaseAccessor Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Represents a database accessor, specialized in retrieving item information.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class ItemDatabaseAccessor _
    Inherits DatabaseAccessor _
    Implements IItemDataManager
'Usage
Dim instance As ItemDatabaseAccessor
```

``` csharp
public sealed class ItemDatabaseAccessor : DatabaseAccessor, 
    IItemDataManager
```

``` c++
public ref class ItemDatabaseAccessor sealed : public DatabaseAccessor, 
    IItemDataManager
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Data.DataStoreAccessor](datastoreaccessor-class-microsoft-dynamics-commerce-runtime-data.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseAccessor](databaseaccessor-class-microsoft-dynamics-commerce-runtime-data.md)  
      Microsoft.Dynamics.Commerce.Runtime.Data.ItemDatabaseAccessor  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

