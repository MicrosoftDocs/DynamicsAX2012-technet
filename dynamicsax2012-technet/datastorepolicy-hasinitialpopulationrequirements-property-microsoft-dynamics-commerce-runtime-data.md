---
title: DataStorePolicy.HasInitialPopulationRequirements Property  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: HasInitialPopulationRequirements Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.DataStorePolicy.HasInitialPopulationRequirements
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.datastorepolicy.hasinitialpopulationrequirements(v=AX.60)
ms:contentKeyID: 62207461
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.DataStorePolicy.HasInitialPopulationRequirements
dev_langs:
- CSharp
- C++
- VB
---

# HasInitialPopulationRequirements Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a value indicating whether the data store requires initial data population.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public ReadOnly Property HasInitialPopulationRequirements As Boolean
    Get
'Usage
Dim instance As DataStorePolicy
Dim value As Boolean

value = instance.HasInitialPopulationRequirements
```

``` csharp
public bool HasInitialPopulationRequirements { get; }
```

``` c++
public:
property bool HasInitialPopulationRequirements {
    bool get ();
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[DataStorePolicy Class](datastorepolicy-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

