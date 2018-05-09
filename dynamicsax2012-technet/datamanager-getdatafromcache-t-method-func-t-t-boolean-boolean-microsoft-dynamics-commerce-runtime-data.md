---
title: DataManager.GetDataFromCache(T) Method (Func(T), T, Boolean, Boolean) (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetDataFromCache(T) Method (Func(T), T, Boolean, Boolean)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.DataManager.GetDataFromCache``1(System.Func{``0},``0,System.Boolean@,System.Boolean@)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn969360(v=AX.60)
ms:contentKeyID: 65322973
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetDataFromCache(T) Method (Func(T), T, Boolean, Boolean)

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Protected Shared Function GetDataFromCache(Of T As {Structure, New, IEquatable(Of T)}) ( _
    searchInCacheDelegate As Func(Of T), _
    notFoundValue As T, _
    <OutAttribute> ByRef found As Boolean, _
    <OutAttribute> ByRef updateCache As Boolean _
) As T
'Usage
Dim searchInCacheDelegate As Func(Of T)
Dim notFoundValue As T
Dim found As Boolean
Dim updateCache As Boolean
Dim returnValue As T

returnValue = DataManager.GetDataFromCache(searchInCacheDelegate, _
    notFoundValue, found, updateCache)
```

``` csharp
protected static T GetDataFromCache<T>(
    Func<T> searchInCacheDelegate,
    T notFoundValue,
    out bool found,
    out bool updateCache
)
where T : struct, new(), IEquatable<T>
```

``` c++
protected:
generic<typename T>
where T : value class, gcnew(), IEquatable<T>
static T GetDataFromCache(
    Func<T>^ searchInCacheDelegate, 
    T notFoundValue, 
    [OutAttribute] bool% found, 
    [OutAttribute] bool% updateCache
)
```

#### Type Parameters

  - T

#### Parameters

  - searchInCacheDelegate  
    Type: [System.Func](https://technet.microsoft.com/en-us/library/bb534960\(v=ax.60\))\<T\>  

<!-- end list -->

  - notFoundValue  
    Type: T  

<!-- end list -->

  - found  
    Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - updateCache  
    Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  

#### Return Value

Type: T  

## See Also

#### Reference

[DataManager Class](datamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[GetDataFromCache\<T\> Overload](datamanager-getdatafromcache-t-method-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

