---
title: DataStoreManager.DataStores Property  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: DataStores Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.DataStoreManager.DataStores
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.datastoremanager.datastores(v=AX.60)
ms:contentKeyID: 62207575
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.DataStoreManager.DataStores
dev_langs:
- CSharp
- C++
- VB
---

# DataStores Property

Gets the managed data stores.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Shared ReadOnly Property DataStores As IDictionary(Of DataStoreType, IDataStore)
    Get
'Usage
Dim value As IDictionary(Of DataStoreType, IDataStore)

value = DataStoreManager.DataStores
```

``` csharp
public static IDictionary<DataStoreType, IDataStore> DataStores { get; }
```

``` c++
public:
static property IDictionary<DataStoreType, IDataStore^>^ DataStores {
    IDictionary<DataStoreType, IDataStore^>^ get ();
}
```

#### Property Value

Type: [System.Collections.Generic.IDictionary](https://technet.microsoft.com/en-us/library/s4ys34ea\(v=ax.60\))\<[DataStoreType](datastoretype-enumeration-microsoft-dynamics-commerce-runtime-data.md), [IDataStore](idatastore-interface-microsoft-dynamics-commerce-runtime-data.md)\>  
Returns [IDictionary\<TKey, TValue\>](https://technet.microsoft.com/en-us/library/s4ys34ea\(v=ax.60\)).  

## See Also

#### Reference

[DataStoreManager Class](datastoremanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

