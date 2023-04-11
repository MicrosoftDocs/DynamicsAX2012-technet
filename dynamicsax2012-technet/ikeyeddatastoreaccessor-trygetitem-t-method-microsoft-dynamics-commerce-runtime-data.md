---
title: IKeyedDataStoreAccessor.TryGetItem(T) Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: TryGetItem(T) Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.IKeyedDataStoreAccessor.TryGetItem``1(System.String,``0@,Microsoft.Dynamics.Commerce.Runtime.Data.IDataStore)
ms:mtpsurl: https://technet.microsoft.com/library/Dn991291(v=AX.60)
ms:contentKeyID: 65323230
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.IKeyedDataStoreAccessor.TryGetItem``1
dev_langs:
- CSharp
- C++
- VB
---

# TryGetItem(T) Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Function TryGetItem(Of T) ( _
    key As String, _
    <OutAttribute> ByRef item As T, _
    currentStore As IDataStore _
) As Boolean
'Usage
Dim instance As IKeyedDataStoreAccessor
Dim key As String
Dim item As T
Dim currentStore As IDataStore
Dim returnValue As Boolean

returnValue = instance.TryGetItem(key, _
    item, currentStore)
```

``` csharp
bool TryGetItem<T>(
    string key,
    out T item,
    IDataStore currentStore
)
```

``` c++
generic<typename T>
bool TryGetItem(
    String^ key, 
    [OutAttribute] T% item, 
    IDataStore^ currentStore
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

<!-- end list -->

  - currentStore  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.IDataStore](idatastore-interface-microsoft-dynamics-commerce-runtime-data.md)  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[IKeyedDataStoreAccessor Interface](ikeyeddatastoreaccessor-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

