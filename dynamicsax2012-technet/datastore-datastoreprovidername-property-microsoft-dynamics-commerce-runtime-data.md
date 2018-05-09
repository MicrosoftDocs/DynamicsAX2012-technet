---
title: DataStore.DataStoreProviderName Property  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: DataStoreProviderName Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.DataStore.DataStoreProviderName
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.datastore.datastoreprovidername(v=AX.60)
ms:contentKeyID: 65321255
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.DataStore.DataStoreProviderName
dev_langs:
- CSharp
- C++
- VB
---

# DataStoreProviderName Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Property DataStoreProviderName As String
    Get
    Set
'Usage
Dim instance As DataStore
Dim value As String

value = instance.DataStoreProviderName

instance.DataStoreProviderName = value
```

``` csharp
public string DataStoreProviderName { get; set; }
```

``` c++
public:
virtual property String^ DataStoreProviderName {
    String^ get () sealed;
    void set (String^ value) sealed;
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Implements

[IDataStore.DataStoreProviderName](idatastore-datastoreprovidername-property-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[DataStore Class](datastore-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

