---
title: DataStore.Store Property  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: Store Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.DataStore.Store
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.datastore.store(v=AX.60)
ms:contentKeyID: 62208162
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.DataStore.Store
dev_langs:
- CSharp
- C++
- VB
---

# Store Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the underlying data store.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Property Store As Object
    Get
    Set
'Usage
Dim instance As DataStore
Dim value As Object

value = instance.Store

instance.Store = value
```

``` csharp
public Object Store { get; set; }
```

``` c++
public:
virtual property Object^ Store {
    Object^ get () sealed;
    void set (Object^ value) sealed;
}
```

#### Property Value

Type: [System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
Returns [IDisposable](https://technet.microsoft.com/library/aax125c9\(v=ax.60\)).  

#### Implements

[IDataStore.Store](idatastore-store-property-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[DataStore Class](datastore-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

