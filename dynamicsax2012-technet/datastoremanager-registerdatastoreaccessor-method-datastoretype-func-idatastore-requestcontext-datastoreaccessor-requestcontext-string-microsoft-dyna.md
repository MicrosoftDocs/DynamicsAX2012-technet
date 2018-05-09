---
title: DataStoreManager.RegisterDataStoreAccessor Method (DataStoreType, Func(IDataStore, RequestContext, DataStoreAccessor), RequestContext, String) (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: RegisterDataStoreAccessor Method (DataStoreType, Func(IDataStore, RequestContext, DataStoreAccessor), RequestContext, String)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.DataStoreManager.RegisterDataStoreAccessor(Microsoft.Dynamics.Commerce.Runtime.Data.DataStoreType,System.Func{Microsoft.Dynamics.Commerce.Runtime.Data.IDataStore,Microsoft.Dynamics.Commerce.Runtime.RequestContext,Microsoft.Dynamics.Commerce.Runtime.Data.DataStoreAccessor},Microsoft.Dynamics.Commerce.Runtime.RequestContext,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.datastoremanager.registerdatastoreaccessor(v=AX.60)
ms:contentKeyID: 65320808
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# RegisterDataStoreAccessor Method (DataStoreType, Func(IDataStore, RequestContext, DataStoreAccessor), RequestContext, String)

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Sub RegisterDataStoreAccessor ( _
    target As DataStoreType, _
    constructor As Func(Of IDataStore, RequestContext, DataStoreAccessor), _
    context As RequestContext, _
    providerName As String _
)
'Usage
Dim instance As DataStoreManager
Dim target As DataStoreType
Dim constructor As Func(Of IDataStore, RequestContext, DataStoreAccessor)
Dim context As RequestContext
Dim providerName As String

instance.RegisterDataStoreAccessor(target, _
    constructor, context, providerName)
```

``` csharp
public void RegisterDataStoreAccessor(
    DataStoreType target,
    Func<IDataStore, RequestContext, DataStoreAccessor> constructor,
    RequestContext context,
    string providerName
)
```

``` c++
public:
void RegisterDataStoreAccessor(
    DataStoreType target, 
    Func<IDataStore^, RequestContext^, DataStoreAccessor^>^ constructor, 
    RequestContext^ context, 
    String^ providerName
)
```

#### Parameters

  - target  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.DataStoreType](datastoretype-enumeration-microsoft-dynamics-commerce-runtime-data.md)  

<!-- end list -->

  - constructor  
    Type: [System.Func](https://technet.microsoft.com/en-us/library/bb534647\(v=ax.60\))\<[IDataStore](idatastore-interface-microsoft-dynamics-commerce-runtime-data.md), [RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md), [DataStoreAccessor](datastoreaccessor-class-microsoft-dynamics-commerce-runtime-data.md)\>  

<!-- end list -->

  - context  
    Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - providerName  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[DataStoreManager Class](datastoremanager-class-microsoft-dynamics-commerce-runtime-data.md)

[RegisterDataStoreAccessor Overload](datastoremanager-registerdatastoreaccessor-method-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

