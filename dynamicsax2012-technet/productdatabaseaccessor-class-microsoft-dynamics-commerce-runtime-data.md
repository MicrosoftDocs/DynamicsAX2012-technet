---
title: ProductDatabaseAccessor Class (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: ProductDatabaseAccessor Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Data.ProductDatabaseAccessor
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.productdatabaseaccessor(v=AX.60)
ms:contentKeyID: 62209764
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ProductDatabaseAccessor
dev_langs:
- CSharp
- C++
- VB
---

# ProductDatabaseAccessor Class

Represents a database accessor, specialized in retrieving listing information.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class ProductDatabaseAccessor _
    Inherits DatabaseAccessor _
    Implements IProductDataManager
'Usage
Dim instance As ProductDatabaseAccessor
```

``` csharp
public sealed class ProductDatabaseAccessor : DatabaseAccessor, 
    IProductDataManager
```

``` c++
public ref class ProductDatabaseAccessor sealed : public DatabaseAccessor, 
    IProductDataManager
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Data.DataStoreAccessor](datastoreaccessor-class-microsoft-dynamics-commerce-runtime-data.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseAccessor](databaseaccessor-class-microsoft-dynamics-commerce-runtime-data.md)  
      Microsoft.Dynamics.Commerce.Runtime.Data.ProductDatabaseAccessor  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

