---
title: ChannelDatabaseAccessor Class (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: ChannelDatabaseAccessor Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Data.ChannelDatabaseAccessor
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.channeldatabaseaccessor(v=AX.60)
ms:contentKeyID: 62214179
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ChannelDatabaseAccessor
dev_langs:
- CSharp
- C++
- VB
---

# ChannelDatabaseAccessor Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Database accessor of the functionality related to channel data management.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class ChannelDatabaseAccessor _
    Inherits DatabaseAccessor _
    Implements IChannelDataManager
'Usage
Dim instance As ChannelDatabaseAccessor
```

``` csharp
public sealed class ChannelDatabaseAccessor : DatabaseAccessor, 
    IChannelDataManager
```

``` c++
public ref class ChannelDatabaseAccessor sealed : public DatabaseAccessor, 
    IChannelDataManager
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Data.DataStoreAccessor](datastoreaccessor-class-microsoft-dynamics-commerce-runtime-data.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseAccessor](databaseaccessor-class-microsoft-dynamics-commerce-runtime-data.md)  
      Microsoft.Dynamics.Commerce.Runtime.Data.ChannelDatabaseAccessor  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

