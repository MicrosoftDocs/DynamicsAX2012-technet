---
title: DataStoreManager.UnregisterDataStoreAccessor Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: UnregisterDataStoreAccessor Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.DataStoreManager.UnregisterDataStoreAccessor(Microsoft.Dynamics.Commerce.Runtime.Data.DataStoreType)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.datastoremanager.unregisterdatastoreaccessor(v=AX.60)
ms:contentKeyID: 62212178
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.DataStoreManager.UnregisterDataStoreAccessor
dev_langs:
- CSharp
- C++
- VB
---

# UnregisterDataStoreAccessor Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Unregisters the data stores for the specified data store type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Sub UnregisterDataStoreAccessor ( _
    target As DataStoreType _
)
'Usage
Dim instance As DataStoreManager
Dim target As DataStoreType

instance.UnregisterDataStoreAccessor(target)
```

``` csharp
public void UnregisterDataStoreAccessor(
    DataStoreType target
)
```

``` c++
public:
void UnregisterDataStoreAccessor(
    DataStoreType target
)
```

#### Parameters

  - target  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.DataStoreType](datastoretype-enumeration-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[DataStoreManager Class](datastoremanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

