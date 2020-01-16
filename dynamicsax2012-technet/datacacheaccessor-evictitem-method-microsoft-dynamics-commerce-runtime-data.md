---
title: DataCacheAccessor.EvictItem Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: EvictItem Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.DataCacheAccessor.EvictItem(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.datacacheaccessor.evictitem(v=AX.60)
ms:contentKeyID: 65322184
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.DataCacheAccessor.EvictItem
dev_langs:
- CSharp
- C++
- VB
---

# EvictItem Method

Evicts from the cache the item with the specified key.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Protected Sub EvictItem ( _
    key As String _
)
'Usage
Dim key As String

Me.EvictItem(key)
```

``` csharp
protected void EvictItem(
    string key
)
```

``` c++
protected:
void EvictItem(
    String^ key
)
```

#### Parameters

  - key  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[DataCacheAccessor Class](datacacheaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

