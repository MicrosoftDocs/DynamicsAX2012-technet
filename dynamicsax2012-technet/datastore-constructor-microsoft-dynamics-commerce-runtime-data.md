---
title: DataStore Constructor  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: DataStore Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.DataStore.#ctor(System.Object,Microsoft.Dynamics.Commerce.Runtime.Data.DataStoreType,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.datastore.datastore(v=AX.60)
ms:contentKeyID: 65319852
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.DataStore.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# DataStore Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    storeValue As Object, _
    type As DataStoreType, _
    dataStoreProviderName As String _
)
'Usage
Dim storeValue As Object
Dim type As DataStoreType
Dim dataStoreProviderName As String

Dim instance As New DataStore(storeValue, _
    type, dataStoreProviderName)
```

``` csharp
public DataStore(
    Object storeValue,
    DataStoreType type,
    string dataStoreProviderName
)
```

``` c++
public:
DataStore(
    Object^ storeValue, 
    DataStoreType type, 
    String^ dataStoreProviderName
)
```

#### Parameters

  - storeValue  
    Type: [System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  

<!-- end list -->

  - type  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.DataStoreType](datastoretype-enumeration-microsoft-dynamics-commerce-runtime-data.md)  

<!-- end list -->

  - dataStoreProviderName  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[DataStore Class](datastore-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

