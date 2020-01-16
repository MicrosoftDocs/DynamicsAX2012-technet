---
title: IDataStore.Store Property  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: Store Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.IDataStore.Store
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.idatastore.store(v=AX.60)
ms:contentKeyID: 65318710
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.IDataStore.Store
dev_langs:
- CSharp
- C++
- VB
---

# Store Property

Gets or sets the underlying data store.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Property Store As Object
    Get
    Set
'Usage
Dim instance As IDataStore
Dim value As Object

value = instance.Store

instance.Store = value
```

``` csharp
Object Store { get; set; }
```

``` c++
property Object^ Store {
    Object^ get ();
    void set (Object^ value);
}
```

#### Property Value

Type: [System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
Returns [Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\)).  

## See Also

#### Reference

[IDataStore Interface](idatastore-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

