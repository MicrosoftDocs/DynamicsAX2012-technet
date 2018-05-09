---
title: DataCacheAccessor.PutItem(T) Method (String, T, DateTimeOffset, TimeSpan) (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: PutItem(T) Method (String, T, DateTimeOffset, TimeSpan)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.DataCacheAccessor.PutItem``1(System.String,``0,System.DateTimeOffset,System.TimeSpan)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn989200(v=AX.60)
ms:contentKeyID: 65319155
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# PutItem(T) Method (String, T, DateTimeOffset, TimeSpan)

Puts an item in the cache under the specified key.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Protected Sub PutItem(Of T) ( _
    key As String, _
    item As T, _
    absoluteExpiration As DateTimeOffset, _
    slidingExpiration As TimeSpan _
)
'Usage
Dim key As String
Dim item As T
Dim absoluteExpiration As DateTimeOffset
Dim slidingExpiration As TimeSpan

Me.PutItem(key, item, absoluteExpiration, _
    slidingExpiration)
```

``` csharp
protected void PutItem<T>(
    string key,
    T item,
    DateTimeOffset absoluteExpiration,
    TimeSpan slidingExpiration
)
```

``` c++
protected:
generic<typename T>
void PutItem(
    String^ key, 
    T item, 
    DateTimeOffset absoluteExpiration, 
    TimeSpan slidingExpiration
)
```

#### Type Parameters

  - T

#### Parameters

  - key  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - item  
    Type: T  

<!-- end list -->

  - absoluteExpiration  
    Type: [System.DateTimeOffset](https://technet.microsoft.com/en-us/library/bb341783\(v=ax.60\))  

<!-- end list -->

  - slidingExpiration  
    Type: [System.TimeSpan](https://technet.microsoft.com/en-us/library/269ew577\(v=ax.60\))  

## See Also

#### Reference

[DataCacheAccessor Class](datacacheaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[PutItem\<T\> Overload](datacacheaccessor-putitem-t-method-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

