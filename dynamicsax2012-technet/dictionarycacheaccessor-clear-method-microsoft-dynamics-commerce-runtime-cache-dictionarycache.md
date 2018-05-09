---
title: DictionaryCacheAccessor.Clear Method  (Microsoft.Dynamics.Commerce.Runtime.Cache.DictionaryCache)
TOCTitle: Clear Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Cache.DictionaryCache.DictionaryCacheAccessor.Clear(Microsoft.Dynamics.Commerce.Runtime.Data.IDataStore)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.cache.dictionarycache.dictionarycacheaccessor.clear(v=AX.60)
ms:contentKeyID: 65316178
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Cache.DictionaryCache.DictionaryCacheAccessor.Clear
dev_langs:
- CSharp
- C++
- VB
---

# Clear Method

Clears all the entities for the given data store.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Cache.DictionaryCache](microsoft-dynamics-commerce-runtime-cache-dictionarycache-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Cache.DictionaryCache (in Microsoft.Dynamics.Commerce.Runtime.Cache.DictionaryCache.dll)

## Syntax

``` vb
'Declaration
Public Sub Clear ( _
    currentStore As IDataStore _
)
'Usage
Dim instance As DictionaryCacheAccessor
Dim currentStore As IDataStore

instance.Clear(currentStore)
```

``` csharp
public void Clear(
    IDataStore currentStore
)
```

``` c++
public:
virtual void Clear(
    IDataStore^ currentStore
) sealed
```

#### Parameters

  - currentStore  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.IDataStore](idatastore-interface-microsoft-dynamics-commerce-runtime-data.md)  

#### Implements

[IKeyedDataStoreAccessor.Clear(IDataStore)](ikeyeddatastoreaccessor-clear-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[DictionaryCacheAccessor Class](dictionarycacheaccessor-class-microsoft-dynamics-commerce-runtime-cache-dictionarycache.md)

[Microsoft.Dynamics.Commerce.Runtime.Cache.DictionaryCache Namespace](microsoft-dynamics-commerce-runtime-cache-dictionarycache-namespace.md)

