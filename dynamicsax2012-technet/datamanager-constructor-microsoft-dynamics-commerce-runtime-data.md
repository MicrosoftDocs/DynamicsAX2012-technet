---
title: DataManager Constructor  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: DataManager Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.DataManager.#ctor(Microsoft.Dynamics.Commerce.Runtime.RequestContext)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.datamanager.datamanager(v=AX.60)
ms:contentKeyID: 62211999
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.DataManager.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# DataManager Constructor

Initializes a new instance of the [DataManager](datamanager-class-microsoft-dynamics-commerce-runtime-data.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Protected Sub New ( _
    context As RequestContext _
)
'Usage
Dim context As RequestContext

Dim instance As New DataManager(context)
```

``` csharp
protected DataManager(
    RequestContext context
)
```

``` c++
protected:
DataManager(
    RequestContext^ context
)
```

#### Parameters

  - context  
    Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  

## See Also

#### Reference

[DataManager Class](datamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

