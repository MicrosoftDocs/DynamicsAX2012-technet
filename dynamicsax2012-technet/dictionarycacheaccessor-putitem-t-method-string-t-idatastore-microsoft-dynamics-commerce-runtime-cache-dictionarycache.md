---
title: DictionaryCacheAccessor.PutItem(T) Method (String, T, IDataStore) (Microsoft.Dynamics.Commerce.Runtime.Cache.DictionaryCache)
TOCTitle: PutItem(T) Method (String, T, IDataStore)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Cache.DictionaryCache.DictionaryCacheAccessor.PutItem``1(System.String,``0,Microsoft.Dynamics.Commerce.Runtime.Data.IDataStore)
ms:mtpsurl: https://technet.microsoft.com/library/Dn966304(v=AX.60)
ms:contentKeyID: 65315492
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# PutItem(T) Method (String, T, IDataStore)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Puts an item in the cache under the specified key.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Cache.DictionaryCache](microsoft-dynamics-commerce-runtime-cache-dictionarycache-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Cache.DictionaryCache (in Microsoft.Dynamics.Commerce.Runtime.Cache.DictionaryCache.dll)

## Syntax

``` vb
'Declaration
Public Sub PutItem(Of T) ( _
    key As String, _
    item As T, _
    currentStore As IDataStore _
)
'Usage
Dim instance As DictionaryCacheAccessor
Dim key As String
Dim item As T
Dim currentStore As IDataStore

instance.PutItem(key, item, currentStore)
```

``` csharp
public void PutItem<T>(
    string key,
    T item,
    IDataStore currentStore
)
```

``` c++
public:
generic<typename T>
virtual void PutItem(
    String^ key, 
    T item, 
    IDataStore^ currentStore
) sealed
```

#### Type Parameters

  - T

#### Parameters

  - key  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - item  
    Type: T  

<!-- end list -->

  - currentStore  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.IDataStore](idatastore-interface-microsoft-dynamics-commerce-runtime-data.md)  

#### Implements

[IKeyedDataStoreAccessor.PutItem\<T\>(String, T, IDataStore)](ikeyeddatastoreaccessor-putitem-t-method-string-t-idatastore-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[DictionaryCacheAccessor Class](dictionarycacheaccessor-class-microsoft-dynamics-commerce-runtime-cache-dictionarycache.md)

[PutItem\<T\> Overload](dictionarycacheaccessor-putitem-t-method-microsoft-dynamics-commerce-runtime-cache-dictionarycache.md)

[Microsoft.Dynamics.Commerce.Runtime.Cache.DictionaryCache Namespace](microsoft-dynamics-commerce-runtime-cache-dictionarycache-namespace.md)

