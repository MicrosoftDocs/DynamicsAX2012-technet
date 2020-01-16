---
title: DataStoreAccessor.StorageResolver Property  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: StorageResolver Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.DataStoreAccessor.StorageResolver
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.datastoreaccessor.storageresolver(v=AX.60)
ms:contentKeyID: 62214250
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.DataStoreAccessor.StorageResolver
dev_langs:
- CSharp
- C++
- VB
---

# StorageResolver Property

Gets or sets the associated storage resolver.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Protected Property StorageResolver As StorageResolver
    Get
    Set
'Usage
Dim value As StorageResolver

value = Me.StorageResolver

Me.StorageResolver = value
```

``` csharp
protected StorageResolver StorageResolver { get; set; }
```

``` c++
protected:
property StorageResolver^ StorageResolver {
    StorageResolver^ get ();
    void set (StorageResolver^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Data.StorageResolver](storageresolver-class-microsoft-dynamics-commerce-runtime-data.md)  
Returns [StorageResolver](storageresolver-class-microsoft-dynamics-commerce-runtime-data.md).  

## See Also

#### Reference

[DataStoreAccessor Class](datastoreaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

