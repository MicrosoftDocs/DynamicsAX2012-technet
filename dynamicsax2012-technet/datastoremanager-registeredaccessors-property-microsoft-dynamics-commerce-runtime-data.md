---
title: DataStoreManager.RegisteredAccessors Property  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: RegisteredAccessors Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.DataStoreManager.RegisteredAccessors
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.datastoremanager.registeredaccessors(v=AX.60)
ms:contentKeyID: 62211714
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.DataStoreManager.RegisteredAccessors
dev_langs:
- CSharp
- C++
- VB
---

# RegisteredAccessors Property

Gets the registered accessors.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public ReadOnly Property RegisteredAccessors As IDictionary(Of DataStoreType, DataStoreAccessor)
    Get
'Usage
Dim instance As DataStoreManager
Dim value As IDictionary(Of DataStoreType, DataStoreAccessor)

value = instance.RegisteredAccessors
```

``` csharp
public IDictionary<DataStoreType, DataStoreAccessor> RegisteredAccessors { get; }
```

``` c++
public:
property IDictionary<DataStoreType, DataStoreAccessor^>^ RegisteredAccessors {
    IDictionary<DataStoreType, DataStoreAccessor^>^ get ();
}
```

#### Property Value

Type: [System.Collections.Generic.IDictionary](https://technet.microsoft.com/en-us/library/s4ys34ea\(v=ax.60\))\<[DataStoreType](datastoretype-enumeration-microsoft-dynamics-commerce-runtime-data.md), [DataStoreAccessor](datastoreaccessor-class-microsoft-dynamics-commerce-runtime-data.md)\>  
Returns [IDictionary\<TKey, TValue\>](https://technet.microsoft.com/en-us/library/s4ys34ea\(v=ax.60\)).  

## See Also

#### Reference

[DataStoreManager Class](datastoremanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

