---
title: DataStoreAccessor.Context Property  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: Context Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.DataStoreAccessor.Context
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.datastoreaccessor.context(v=AX.60)
ms:contentKeyID: 62213732
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.DataStoreAccessor.Context
dev_langs:
- CSharp
- C++
- VB
---

# Context Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the request context.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Property Context As RequestContext
    Get
    Set
'Usage
Dim instance As DataStoreAccessor
Dim value As RequestContext

value = instance.Context

instance.Context = value
```

``` csharp
public RequestContext Context { get; set; }
```

``` c++
public:
property RequestContext^ Context {
    RequestContext^ get ();
    void set (RequestContext^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  
Returns [RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md).  

## See Also

#### Reference

[DataStoreAccessor Class](datastoreaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

