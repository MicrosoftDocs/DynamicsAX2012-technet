---
title: DataStore.DataStoreType Property  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: DataStoreType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.DataStore.DataStoreType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.datastore.datastoretype(v=AX.60)
ms:contentKeyID: 62206107
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.DataStore.DataStoreType
dev_langs:
- CSharp
- C++
- VB
---

# DataStoreType Property

Gets the data store type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Property DataStoreType As DataStoreType
    Get
    Set
'Usage
Dim instance As DataStore
Dim value As DataStoreType

value = instance.DataStoreType

instance.DataStoreType = value
```

``` csharp
public DataStoreType DataStoreType { get; set; }
```

``` c++
public:
virtual property DataStoreType DataStoreType {
    DataStoreType get () sealed;
    void set (DataStoreType value) sealed;
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Data.DataStoreType](datastoretype-enumeration-microsoft-dynamics-commerce-runtime-data.md)  
Returns [DataStoreType](datastoretype-enumeration-microsoft-dynamics-commerce-runtime-data.md).  

#### Implements

[IDataStore.DataStoreType](idatastore-datastoretype-property-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[DataStore Class](datastore-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

