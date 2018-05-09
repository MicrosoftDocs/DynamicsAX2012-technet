---
title: DataStorePolicy.MustUpdateOnMiss Property  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: MustUpdateOnMiss Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.DataStorePolicy.MustUpdateOnMiss
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.datastorepolicy.mustupdateonmiss(v=AX.60)
ms:contentKeyID: 62208767
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.DataStorePolicy.MustUpdateOnMiss
dev_langs:
- CSharp
- C++
- VB
---

# MustUpdateOnMiss Property

Gets a value indicating whether the data store must be updated if an entry is not found.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public ReadOnly Property MustUpdateOnMiss As Boolean
    Get
'Usage
Dim instance As DataStorePolicy
Dim value As Boolean

value = instance.MustUpdateOnMiss
```

``` csharp
public bool MustUpdateOnMiss { get; }
```

``` c++
public:
virtual property bool MustUpdateOnMiss {
    bool get () sealed;
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\)).  

#### Implements

[IDataStorePolicy.MustUpdateOnMiss](idatastorepolicy-mustupdateonmiss-property-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[DataStorePolicy Class](datastorepolicy-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

