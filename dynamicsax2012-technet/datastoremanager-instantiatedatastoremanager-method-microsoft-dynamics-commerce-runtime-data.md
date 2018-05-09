---
title: DataStoreManager.InstantiateDataStoreManager Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: InstantiateDataStoreManager Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.DataStoreManager.InstantiateDataStoreManager(Microsoft.Dynamics.Commerce.Runtime.RequestContext,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.datastoremanager.instantiatedatastoremanager(v=AX.60)
ms:contentKeyID: 65315539
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.DataStoreManager.InstantiateDataStoreManager
dev_langs:
- CSharp
- C++
- VB
---

# InstantiateDataStoreManager Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Shared Function InstantiateDataStoreManager ( _
    requestContext As RequestContext, _
    providerName As String _
) As DataStoreManager
'Usage
Dim requestContext As RequestContext
Dim providerName As String
Dim returnValue As DataStoreManager

returnValue = DataStoreManager.InstantiateDataStoreManager(requestContext, _
    providerName)
```

``` csharp
public static DataStoreManager InstantiateDataStoreManager(
    RequestContext requestContext,
    string providerName
)
```

``` c++
public:
static DataStoreManager^ InstantiateDataStoreManager(
    RequestContext^ requestContext, 
    String^ providerName
)
```

#### Parameters

  - requestContext  
    Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - providerName  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Data.DataStoreManager](datastoremanager-class-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[DataStoreManager Class](datastoremanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

