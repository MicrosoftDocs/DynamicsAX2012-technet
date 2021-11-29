---
title: IDataStore.DataStoreType Property  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: DataStoreType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.IDataStore.DataStoreType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.idatastore.datastoretype(v=AX.60)
ms:contentKeyID: 65317068
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.IDataStore.DataStoreType
dev_langs:
- CSharp
- C++
- VB
---

# DataStoreType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the data store type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Property DataStoreType As DataStoreType
    Get
    Set
'Usage
Dim instance As IDataStore
Dim value As DataStoreType

value = instance.DataStoreType

instance.DataStoreType = value
```

``` csharp
DataStoreType DataStoreType { get; set; }
```

``` c++
property DataStoreType DataStoreType {
    DataStoreType get ();
    void set (DataStoreType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Data.DataStoreType](datastoretype-enumeration-microsoft-dynamics-commerce-runtime-data.md)  
Returns [DataStoreType](datastoretype-enumeration-microsoft-dynamics-commerce-runtime-data.md).  

## See Also

#### Reference

[IDataStore Interface](idatastore-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

