---
title: DataStore.Policy Property  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: Policy Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.DataStore.Policy
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.datastore.policy(v=AX.60)
ms:contentKeyID: 62207787
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.DataStore.Policy
dev_langs:
- CSharp
- C++
- VB
---

# Policy Property

Gets the data store policy.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Property Policy As IDataStorePolicy
    Get
    Set
'Usage
Dim instance As DataStore
Dim value As IDataStorePolicy

value = instance.Policy

instance.Policy = value
```

``` csharp
public IDataStorePolicy Policy { get; set; }
```

``` c++
public:
virtual property IDataStorePolicy^ Policy {
    IDataStorePolicy^ get () sealed;
    void set (IDataStorePolicy^ value) sealed;
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Data.IDataStorePolicy](idatastorepolicy-interface-microsoft-dynamics-commerce-runtime-data.md)  
Returns [DataStorePolicy](datastorepolicy-class-microsoft-dynamics-commerce-runtime-data.md).  

#### Implements

[IDataStore.Policy](idatastore-policy-property-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[DataStore Class](datastore-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

