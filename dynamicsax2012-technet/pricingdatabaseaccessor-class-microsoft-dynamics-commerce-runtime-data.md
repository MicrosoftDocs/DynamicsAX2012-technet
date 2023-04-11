---
title: PricingDatabaseAccessor Class (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: PricingDatabaseAccessor Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Data.PricingDatabaseAccessor
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.pricingdatabaseaccessor(v=AX.60)
ms:contentKeyID: 62212180
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.PricingDatabaseAccessor
dev_langs:
- CSharp
- C++
- VB
---

# PricingDatabaseAccessor Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Encapsulates data access to pricing information.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class PricingDatabaseAccessor _
    Inherits DatabaseAccessor _
    Implements IPricingDataManagerV2, IPricingDataManager
'Usage
Dim instance As PricingDatabaseAccessor
```

``` csharp
public sealed class PricingDatabaseAccessor : DatabaseAccessor, 
    IPricingDataManagerV2, IPricingDataManager
```

``` c++
public ref class PricingDatabaseAccessor sealed : public DatabaseAccessor, 
    IPricingDataManagerV2, IPricingDataManager
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Data.DataStoreAccessor](datastoreaccessor-class-microsoft-dynamics-commerce-runtime-data.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseAccessor](databaseaccessor-class-microsoft-dynamics-commerce-runtime-data.md)  
      Microsoft.Dynamics.Commerce.Runtime.Data.PricingDatabaseAccessor  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

