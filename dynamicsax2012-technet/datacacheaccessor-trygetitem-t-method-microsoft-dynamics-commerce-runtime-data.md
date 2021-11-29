---
title: DataCacheAccessor.TryGetItem(T) Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: TryGetItem(T) Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.DataCacheAccessor.TryGetItem``1(System.String,``0@)
ms:mtpsurl: https://technet.microsoft.com/library/Dn988107(v=AX.60)
ms:contentKeyID: 65317155
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.DataCacheAccessor.TryGetItem``1
dev_langs:
- CSharp
- C++
- VB
---

# TryGetItem(T) Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Attempts to extract the item stored in the cache under the specified key.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Protected Function TryGetItem(Of T) ( _
    key As String, _
    <OutAttribute> ByRef item As T _
) As Boolean
'Usage
Dim key As String
Dim item As T
Dim returnValue As Boolean

returnValue = Me.TryGetItem(key, item)
```

``` csharp
protected bool TryGetItem<T>(
    string key,
    out T item
)
```

``` c++
protected:
generic<typename T>
bool TryGetItem(
    String^ key, 
    [OutAttribute] T% item
)
```

#### Type Parameters

  - T

#### Parameters

  - key  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - item  
    Type: T  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
True if the key exists in the memory cache.  

## See Also

#### Reference

[DataCacheAccessor Class](datacacheaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

