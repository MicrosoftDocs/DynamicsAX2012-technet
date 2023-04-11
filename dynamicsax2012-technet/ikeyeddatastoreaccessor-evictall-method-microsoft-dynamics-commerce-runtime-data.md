---
title: IKeyedDataStoreAccessor.EvictAll Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: EvictAll Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.IKeyedDataStoreAccessor.EvictAll(System.String,Microsoft.Dynamics.Commerce.Runtime.Data.IDataStore)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.ikeyeddatastoreaccessor.evictall(v=AX.60)
ms:contentKeyID: 65321999
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.IKeyedDataStoreAccessor.EvictAll
dev_langs:
- CSharp
- C++
- VB
---

# EvictAll Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Sub EvictAll ( _
    keyPattern As String, _
    currentStore As IDataStore _
)
'Usage
Dim instance As IKeyedDataStoreAccessor
Dim keyPattern As String
Dim currentStore As IDataStore

instance.EvictAll(keyPattern, currentStore)
```

``` csharp
void EvictAll(
    string keyPattern,
    IDataStore currentStore
)
```

``` c++
void EvictAll(
    String^ keyPattern, 
    IDataStore^ currentStore
)
```

#### Parameters

  - keyPattern  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - currentStore  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.IDataStore](idatastore-interface-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[IKeyedDataStoreAccessor Interface](ikeyeddatastoreaccessor-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

