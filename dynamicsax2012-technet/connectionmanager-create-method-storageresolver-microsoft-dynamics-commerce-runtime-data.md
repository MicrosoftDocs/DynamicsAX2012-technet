---
title: ConnectionManager.Create Method (StorageResolver) (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: Create Method (StorageResolver)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ConnectionManager.Create(Microsoft.Dynamics.Commerce.Runtime.Data.StorageResolver)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.connectionmanager.create(v=AX.60)
ms:contentKeyID: 65319321
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# Create Method (StorageResolver)

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Data (in Microsoft.Dynamics.Commerce.Runtime.Data.dll)

## Syntax

``` vb
'Declaration
Public Shared Function Create ( _
    resolver As StorageResolver _
) As ConnectionManager
'Usage
Dim resolver As StorageResolver
Dim returnValue As ConnectionManager

returnValue = ConnectionManager.Create(resolver)
```

``` csharp
public static ConnectionManager Create(
    StorageResolver resolver
)
```

``` c++
public:
static ConnectionManager^ Create(
    StorageResolver^ resolver
)
```

#### Parameters

  - resolver  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.StorageResolver](storageresolver-class-microsoft-dynamics-commerce-runtime-data.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Data.ConnectionManager](connectionmanager-class-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[ConnectionManager Class](connectionmanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Create Overload](connectionmanager-create-method-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

