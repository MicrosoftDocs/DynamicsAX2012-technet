---
title: DataStoreAccessor Constructor (IDataStore, RequestContext) (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: DataStoreAccessor Constructor (IDataStore, RequestContext)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.DataStoreAccessor.#ctor(Microsoft.Dynamics.Commerce.Runtime.Data.IDataStore,Microsoft.Dynamics.Commerce.Runtime.RequestContext)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.datastoreaccessor.datastoreaccessor(v=AX.60)
ms:contentKeyID: 65322483
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# DataStoreAccessor Constructor (IDataStore, RequestContext)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

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

Dim instance As New DataStoreAccessor(dataStore, _
    context)
```

``` csharp
protected DataStoreAccessor(
    IDataStore dataStore,
    RequestContext context
)
```

``` c++
protected:
DataStoreAccessor(
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

[DataStoreAccessor Class](datastoreaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[DataStoreAccessor Overload](datastoreaccessor-constructor-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

