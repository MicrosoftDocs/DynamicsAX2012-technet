---
title: DataStoreAccessor Class (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: DataStoreAccessor Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Data.DataStoreAccessor
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.datastoreaccessor(v=AX.60)
ms:contentKeyID: 62208058
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.DataStoreAccessor
dev_langs:
- CSharp
- C++
- VB
---

# DataStoreAccessor Class

Class modeling the behavior of a data store accessor.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public MustInherit Class DataStoreAccessor
'Usage
Dim instance As DataStoreAccessor
```

``` csharp
public abstract class DataStoreAccessor
```

``` c++
public ref class DataStoreAccessor abstract
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  Microsoft.Dynamics.Commerce.Runtime.Data.DataStoreAccessor  
    [Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseAccessor](databaseaccessor-class-microsoft-dynamics-commerce-runtime-data.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Data.DataCacheAccessor](datacacheaccessor-class-microsoft-dynamics-commerce-runtime-data.md)  
    [Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite.GetTaxCodeIntervalsProcedure](gettaxcodeintervalsprocedure-class-microsoft-dynamics-commerce-runtime-dataservices-sqlite.md)  
    [Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite.NumberSequenceSqliteDatabaseAccessor](numbersequencesqlitedatabaseaccessor-class-microsoft-dynamics-commerce-runtime-dataservices-sqlite.md)  
    [Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite.ShiftsSqliteDatabaseAccessor](shiftssqlitedatabaseaccessor-class-microsoft-dynamics-commerce-runtime-dataservices-sqlite.md)  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

