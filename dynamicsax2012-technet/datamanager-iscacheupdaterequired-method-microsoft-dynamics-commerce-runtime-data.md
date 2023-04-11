---
title: DataManager.IsCacheUpdateRequired Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: IsCacheUpdateRequired Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.DataManager.IsCacheUpdateRequired(System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.datamanager.iscacheupdaterequired(v=AX.60)
ms:contentKeyID: 62204147
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.DataManager.IsCacheUpdateRequired
dev_langs:
- CSharp
- C++
- VB
---

# IsCacheUpdateRequired Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Determines if cache update is required based on cache policy.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Protected Shared Function IsCacheUpdateRequired ( _
    resultFoundInCache As Boolean _
) As Boolean
'Usage
Dim resultFoundInCache As Boolean
Dim returnValue As Boolean

returnValue = DataManager.IsCacheUpdateRequired(resultFoundInCache)
```

``` csharp
protected static bool IsCacheUpdateRequired(
    bool resultFoundInCache
)
```

``` c++
protected:
static bool IsCacheUpdateRequired(
    bool resultFoundInCache
)
```

#### Parameters

  - resultFoundInCache  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
The value indicating whether cache update is required.  

## See Also

#### Reference

[DataManager Class](datamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

