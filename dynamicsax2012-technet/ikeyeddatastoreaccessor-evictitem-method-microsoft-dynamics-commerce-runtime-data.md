---
title: IKeyedDataStoreAccessor.EvictItem Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: EvictItem Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.IKeyedDataStoreAccessor.EvictItem(System.String,Microsoft.Dynamics.Commerce.Runtime.Data.IDataStore)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.ikeyeddatastoreaccessor.evictitem(v=AX.60)
ms:contentKeyID: 65319894
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.IKeyedDataStoreAccessor.EvictItem
dev_langs:
- CSharp
- C++
- VB
---

# EvictItem Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Sub EvictItem ( _
    key As String, _
    currentStore As IDataStore _
)
'Usage
Dim instance As IKeyedDataStoreAccessor
Dim key As String
Dim currentStore As IDataStore

instance.EvictItem(key, currentStore)
```

``` csharp
void EvictItem(
    string key,
    IDataStore currentStore
)
```

``` c++
void EvictItem(
    String^ key, 
    IDataStore^ currentStore
)
```

#### Parameters

  - key  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - currentStore  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.IDataStore](idatastore-interface-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[IKeyedDataStoreAccessor Interface](ikeyeddatastoreaccessor-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

