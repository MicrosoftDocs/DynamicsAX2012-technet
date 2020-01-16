---
title: DataStoreManager.RegisterDataStoreAccessor Method (DataStoreType, Func(IDataStore, String, DataStoreAccessor), String) (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: RegisterDataStoreAccessor Method (DataStoreType, Func(IDataStore, String, DataStoreAccessor), String)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.DataStoreManager.RegisterDataStoreAccessor(Microsoft.Dynamics.Commerce.Runtime.Data.DataStoreType,System.Func{Microsoft.Dynamics.Commerce.Runtime.Data.IDataStore,System.String,Microsoft.Dynamics.Commerce.Runtime.Data.DataStoreAccessor},System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.datastoremanager.registerdatastoreaccessor(v=AX.60)
ms:contentKeyID: 65317743
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# RegisterDataStoreAccessor Method (DataStoreType, Func(IDataStore, String, DataStoreAccessor), String)

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Sub RegisterDataStoreAccessor ( _
    target As DataStoreType, _
    constructor As Func(Of IDataStore, String, DataStoreAccessor), _
    connectionString As String _
)
'Usage
Dim instance As DataStoreManager
Dim target As DataStoreType
Dim constructor As Func(Of IDataStore, String, DataStoreAccessor)
Dim connectionString As String

instance.RegisterDataStoreAccessor(target, _
    constructor, connectionString)
```

``` csharp
public void RegisterDataStoreAccessor(
    DataStoreType target,
    Func<IDataStore, string, DataStoreAccessor> constructor,
    string connectionString
)
```

``` c++
public:
void RegisterDataStoreAccessor(
    DataStoreType target, 
    Func<IDataStore^, String^, DataStoreAccessor^>^ constructor, 
    String^ connectionString
)
```

#### Parameters

  - target  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.DataStoreType](datastoretype-enumeration-microsoft-dynamics-commerce-runtime-data.md)  

<!-- end list -->

  - constructor  
    Type: [System.Func](https://technet.microsoft.com/library/bb534647\(v=ax.60\))\<[IDataStore](idatastore-interface-microsoft-dynamics-commerce-runtime-data.md), [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)), [DataStoreAccessor](datastoreaccessor-class-microsoft-dynamics-commerce-runtime-data.md)\>  

<!-- end list -->

  - connectionString  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[DataStoreManager Class](datastoremanager-class-microsoft-dynamics-commerce-runtime-data.md)

[RegisterDataStoreAccessor Overload](datastoremanager-registerdatastoreaccessor-method-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

