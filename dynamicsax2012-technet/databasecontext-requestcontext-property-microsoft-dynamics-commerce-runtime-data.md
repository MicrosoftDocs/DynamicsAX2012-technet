---
title: DatabaseContext.RequestContext Property  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: RequestContext Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseContext.RequestContext
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.databasecontext.requestcontext(v=AX.60)
ms:contentKeyID: 65320965
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseContext.RequestContext
dev_langs:
- CSharp
- C++
- VB
---

# RequestContext Property

Gets the request context.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Data (in Microsoft.Dynamics.Commerce.Runtime.Data.dll)

## Syntax

``` vb
'Declaration
Protected Property RequestContext As RequestContext
    Get
    Private Set
'Usage
Dim value As RequestContext

value = Me.RequestContext
```

``` csharp
protected RequestContext RequestContext { get; private set; }
```

``` c++
protected:
property RequestContext^ RequestContext {
    RequestContext^ get ();
    private: void set (RequestContext^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  
Returns [RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md).  

## See Also

#### Reference

[DatabaseContext Class](databasecontext-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

