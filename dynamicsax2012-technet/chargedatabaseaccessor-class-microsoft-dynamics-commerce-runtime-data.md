---
title: ChargeDatabaseAccessor Class (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: ChargeDatabaseAccessor Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Data.ChargeDatabaseAccessor
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.chargedatabaseaccessor(v=AX.60)
ms:contentKeyID: 65316869
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ChargeDatabaseAccessor
dev_langs:
- CSharp
- C++
- VB
---

# ChargeDatabaseAccessor Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Database accessor for the charge data manager.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Class ChargeDatabaseAccessor _
    Inherits DatabaseAccessor _
    Implements IChargeDataManager
'Usage
Dim instance As ChargeDatabaseAccessor
```

``` csharp
public class ChargeDatabaseAccessor : DatabaseAccessor, 
    IChargeDataManager
```

``` c++
public ref class ChargeDatabaseAccessor : public DatabaseAccessor, 
    IChargeDataManager
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Data.DataStoreAccessor](datastoreaccessor-class-microsoft-dynamics-commerce-runtime-data.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseAccessor](databaseaccessor-class-microsoft-dynamics-commerce-runtime-data.md)  
      Microsoft.Dynamics.Commerce.Runtime.Data.ChargeDatabaseAccessor  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

