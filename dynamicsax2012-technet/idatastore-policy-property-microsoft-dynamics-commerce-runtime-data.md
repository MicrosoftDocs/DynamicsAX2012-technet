---
title: IDataStore.Policy Property  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: Policy Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.IDataStore.Policy
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.idatastore.policy(v=AX.60)
ms:contentKeyID: 65321104
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.IDataStore.Policy
dev_langs:
- CSharp
- C++
- VB
---

# Policy Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the data store policy.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Property Policy As IDataStorePolicy
    Get
    Set
'Usage
Dim instance As IDataStore
Dim value As IDataStorePolicy

value = instance.Policy

instance.Policy = value
```

``` csharp
IDataStorePolicy Policy { get; set; }
```

``` c++
property IDataStorePolicy^ Policy {
    IDataStorePolicy^ get ();
    void set (IDataStorePolicy^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Data.IDataStorePolicy](idatastorepolicy-interface-microsoft-dynamics-commerce-runtime-data.md)  
Returns [IDataStorePolicy](idatastorepolicy-interface-microsoft-dynamics-commerce-runtime-data.md).  

## See Also

#### Reference

[IDataStore Interface](idatastore-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

