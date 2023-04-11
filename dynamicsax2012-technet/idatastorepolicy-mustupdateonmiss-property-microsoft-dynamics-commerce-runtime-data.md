---
title: IDataStorePolicy.MustUpdateOnMiss Property  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: MustUpdateOnMiss Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.IDataStorePolicy.MustUpdateOnMiss
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.idatastorepolicy.mustupdateonmiss(v=AX.60)
ms:contentKeyID: 65322655
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.IDataStorePolicy.MustUpdateOnMiss
dev_langs:
- CSharp
- C++
- VB
---

# MustUpdateOnMiss Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a value indicating whether the data store must be updated if an entry is not found.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property MustUpdateOnMiss As Boolean
    Get
'Usage
Dim instance As IDataStorePolicy
Dim value As Boolean

value = instance.MustUpdateOnMiss
```

``` csharp
bool MustUpdateOnMiss { get; }
```

``` c++
property bool MustUpdateOnMiss {
    bool get ();
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[IDataStorePolicy Interface](idatastorepolicy-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

