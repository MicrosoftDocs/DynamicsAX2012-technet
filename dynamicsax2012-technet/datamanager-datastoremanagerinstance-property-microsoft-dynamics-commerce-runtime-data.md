---
title: DataManager.DataStoreManagerInstance Property  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: DataStoreManagerInstance Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.DataManager.DataStoreManagerInstance
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.datamanager.datastoremanagerinstance(v=AX.60)
ms:contentKeyID: 62212237
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.DataManager.DataStoreManagerInstance
dev_langs:
- CSharp
- C++
- VB
---

# DataStoreManagerInstance Property

Gets or sets the instance of the associated data store manager object.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Property DataStoreManagerInstance As DataStoreManager
    Get
    Protected Set
'Usage
Dim instance As DataManager
Dim value As DataStoreManager

value = instance.DataStoreManagerInstance

instance.DataStoreManagerInstance = value
```

``` csharp
public DataStoreManager DataStoreManagerInstance { get; protected set; }
```

``` c++
public:
property DataStoreManager^ DataStoreManagerInstance {
    DataStoreManager^ get ();
    protected: void set (DataStoreManager^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Data.DataStoreManager](datastoremanager-class-microsoft-dynamics-commerce-runtime-data.md)  
Returns [DataStoreManager](datastoremanager-class-microsoft-dynamics-commerce-runtime-data.md).  

## See Also

#### Reference

[DataManager Class](datamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

