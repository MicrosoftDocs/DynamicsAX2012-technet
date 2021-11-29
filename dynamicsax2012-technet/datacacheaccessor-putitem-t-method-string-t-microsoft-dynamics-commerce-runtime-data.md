---
title: DataCacheAccessor.PutItem(T) Method (String, T) (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: PutItem(T) Method (String, T)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.DataCacheAccessor.PutItem``1(System.String,``0)
ms:mtpsurl: https://technet.microsoft.com/library/Dn991265(v=AX.60)
ms:contentKeyID: 65322696
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# PutItem(T) Method (String, T)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Puts an item in the cache under the specified key.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Protected Sub PutItem(Of T) ( _
    key As String, _
    item As T _
)
'Usage
Dim key As String
Dim item As T

Me.PutItem(key, item)
```

``` csharp
protected void PutItem<T>(
    string key,
    T item
)
```

``` c++
protected:
generic<typename T>
void PutItem(
    String^ key, 
    T item
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

## See Also

#### Reference

[DataCacheAccessor Class](datacacheaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[PutItem\<T\> Overload](datacacheaccessor-putitem-t-method-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

