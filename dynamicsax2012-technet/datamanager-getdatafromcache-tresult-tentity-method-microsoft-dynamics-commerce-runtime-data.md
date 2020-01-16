---
title: DataManager.GetDataFromCache(TResult, TEntity) Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetDataFromCache(TResult, TEntity) Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.DataManager.GetDataFromCache``2(System.Func{``0},System.Boolean@,System.Boolean@)
ms:mtpsurl: https://technet.microsoft.com/library/Dn968942(v=AX.60)
ms:contentKeyID: 65322306
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.DataManager.GetDataFromCache``2
dev_langs:
- CSharp
- C++
- VB
---

# GetDataFromCache(TResult, TEntity) Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Protected Shared Function GetDataFromCache(Of TResult As CommerceEntitySearchResult(Of TEntity), TEntity As CommerceEntity) ( _
    searchInCacheDelegate As Func(Of TResult), _
    <OutAttribute> ByRef found As Boolean, _
    <OutAttribute> ByRef updateCache As Boolean _
) As TResult
'Usage
Dim searchInCacheDelegate As Func(Of TResult)
Dim found As Boolean
Dim updateCache As Boolean
Dim returnValue As TResult

returnValue = DataManager.GetDataFromCache(searchInCacheDelegate, _
    found, updateCache)
```

``` csharp
protected static TResult GetDataFromCache<TResult, TEntity>(
    Func<TResult> searchInCacheDelegate,
    out bool found,
    out bool updateCache
)
where TResult : CommerceEntitySearchResult<TEntity>
where TEntity : CommerceEntity
```

``` c++
protected:
generic<typename TResult, typename TEntity>
where TResult : CommerceEntitySearchResult<TEntity>
where TEntity : CommerceEntity
static TResult GetDataFromCache(
    Func<TResult>^ searchInCacheDelegate, 
    [OutAttribute] bool% found, 
    [OutAttribute] bool% updateCache
)
```

#### Type Parameters

  - TResult

<!-- end list -->

  - TEntity

#### Parameters

  - searchInCacheDelegate  
    Type: [System.Func](https://technet.microsoft.com/library/bb534960\(v=ax.60\))\<TResult\>  

<!-- end list -->

  - found  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - updateCache  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

#### Return Value

Type: TResult  

## See Also

#### Reference

[DataManager Class](datamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

