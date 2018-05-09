---
title: DataCacheAccessor Constructor (IDataStore, RequestContext) (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: DataCacheAccessor Constructor (IDataStore, RequestContext)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.DataCacheAccessor.#ctor(Microsoft.Dynamics.Commerce.Runtime.Data.IDataStore,Microsoft.Dynamics.Commerce.Runtime.RequestContext)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.datacacheaccessor.datacacheaccessor(v=AX.60)
ms:contentKeyID: 65322148
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# DataCacheAccessor Constructor (IDataStore, RequestContext)

Initializes a new instance of the [DataCacheAccessor](datacacheaccessor-class-microsoft-dynamics-commerce-runtime-data.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Protected Sub New ( _
    backingStore As IDataStore, _
    context As RequestContext _
)
'Usage
Dim backingStore As IDataStore
Dim context As RequestContext

Dim instance As New DataCacheAccessor(backingStore, _
    context)
```

``` csharp
protected DataCacheAccessor(
    IDataStore backingStore,
    RequestContext context
)
```

``` c++
protected:
DataCacheAccessor(
    IDataStore^ backingStore, 
    RequestContext^ context
)
```

#### Parameters

  - backingStore  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.IDataStore](idatastore-interface-microsoft-dynamics-commerce-runtime-data.md)  

<!-- end list -->

  - context  
    Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  

## See Also

#### Reference

[DataCacheAccessor Class](datacacheaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[DataCacheAccessor Overload](datacacheaccessor-constructor-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

