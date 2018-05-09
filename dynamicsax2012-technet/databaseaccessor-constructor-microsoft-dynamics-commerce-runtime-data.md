---
title: DatabaseAccessor Constructor  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: DatabaseAccessor Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseAccessor.#ctor(Microsoft.Dynamics.Commerce.Runtime.Data.IDataStore,Microsoft.Dynamics.Commerce.Runtime.RequestContext)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.databaseaccessor.databaseaccessor(v=AX.60)
ms:contentKeyID: 65322654
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseAccessor.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# DatabaseAccessor Constructor

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Protected Sub New ( _
    dataStore As IDataStore, _
    context As RequestContext _
)
'Usage
Dim dataStore As IDataStore
Dim context As RequestContext

Dim instance As New DatabaseAccessor(dataStore, _
    context)
```

``` csharp
protected DatabaseAccessor(
    IDataStore dataStore,
    RequestContext context
)
```

``` c++
protected:
DatabaseAccessor(
    IDataStore^ dataStore, 
    RequestContext^ context
)
```

#### Parameters

  - dataStore  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.IDataStore](idatastore-interface-microsoft-dynamics-commerce-runtime-data.md)  

<!-- end list -->

  - context  
    Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  

## See Also

#### Reference

[DatabaseAccessor Class](databaseaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

