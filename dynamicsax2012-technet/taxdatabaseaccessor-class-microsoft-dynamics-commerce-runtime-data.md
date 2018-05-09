---
title: TaxDatabaseAccessor Class (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: TaxDatabaseAccessor Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Data.TaxDatabaseAccessor
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.taxdatabaseaccessor(v=AX.60)
ms:contentKeyID: 62208472
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.TaxDatabaseAccessor
dev_langs:
- CSharp
- C++
- VB
---

# TaxDatabaseAccessor Class

Tax Data manager.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Class TaxDatabaseAccessor _
    Inherits DatabaseAccessor _
    Implements ITaxDataManager
'Usage
Dim instance As TaxDatabaseAccessor
```

``` csharp
public class TaxDatabaseAccessor : DatabaseAccessor, 
    ITaxDataManager
```

``` c++
public ref class TaxDatabaseAccessor : public DatabaseAccessor, 
    ITaxDataManager
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Data.DataStoreAccessor](datastoreaccessor-class-microsoft-dynamics-commerce-runtime-data.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseAccessor](databaseaccessor-class-microsoft-dynamics-commerce-runtime-data.md)  
      Microsoft.Dynamics.Commerce.Runtime.Data.TaxDatabaseAccessor  
        [Microsoft.Dynamics.Commerce.Runtime.Data.IndiaTaxDatabaseAccessor](indiataxdatabaseaccessor-class-microsoft-dynamics-commerce-runtime-data.md)  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

