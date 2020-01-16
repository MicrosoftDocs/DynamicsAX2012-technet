---
title: DataManager.Context Property  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: Context Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.DataManager.Context
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.datamanager.context(v=AX.60)
ms:contentKeyID: 62210373
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.DataManager.Context
dev_langs:
- CSharp
- C++
- VB
---

# Context Property

Gets or sets the context of the current request.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Property Context As RequestContext
    Get
    Protected Set
'Usage
Dim instance As DataManager
Dim value As RequestContext

value = instance.Context

instance.Context = value
```

``` csharp
public RequestContext Context { get; protected set; }
```

``` c++
public:
property RequestContext^ Context {
    RequestContext^ get ();
    protected: void set (RequestContext^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  
Returns [RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md).  

## See Also

#### Reference

[DataManager Class](datamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

