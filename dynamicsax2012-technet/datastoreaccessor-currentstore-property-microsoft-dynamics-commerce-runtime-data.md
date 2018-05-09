---
title: DataStoreAccessor.CurrentStore Property  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: CurrentStore Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.DataStoreAccessor.CurrentStore
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.datastoreaccessor.currentstore(v=AX.60)
ms:contentKeyID: 62214535
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.DataStoreAccessor.CurrentStore
dev_langs:
- CSharp
- C++
- VB
---

# CurrentStore Property

Gets or sets the current backing data store.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Property CurrentStore As IDataStore
    Get
    Protected Set
'Usage
Dim instance As DataStoreAccessor
Dim value As IDataStore

value = instance.CurrentStore

instance.CurrentStore = value
```

``` csharp
public IDataStore CurrentStore { get; protected set; }
```

``` c++
public:
property IDataStore^ CurrentStore {
    IDataStore^ get ();
    protected: void set (IDataStore^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Data.IDataStore](idatastore-interface-microsoft-dynamics-commerce-runtime-data.md)  
Returns [DataStore](datastore-class-microsoft-dynamics-commerce-runtime-data.md).  

## See Also

#### Reference

[DataStoreAccessor Class](datastoreaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

