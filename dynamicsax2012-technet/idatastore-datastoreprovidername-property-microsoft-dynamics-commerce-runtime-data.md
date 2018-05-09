---
title: IDataStore.DataStoreProviderName Property  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: DataStoreProviderName Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.IDataStore.DataStoreProviderName
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.idatastore.datastoreprovidername(v=AX.60)
ms:contentKeyID: 65323114
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.IDataStore.DataStoreProviderName
dev_langs:
- CSharp
- C++
- VB
---

# DataStoreProviderName Property

Gets or sets the data store provider name.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Property DataStoreProviderName As String
    Get
    Set
'Usage
Dim instance As IDataStore
Dim value As String

value = instance.DataStoreProviderName

instance.DataStoreProviderName = value
```

``` csharp
string DataStoreProviderName { get; set; }
```

``` c++
property String^ DataStoreProviderName {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[IDataStore Interface](idatastore-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

