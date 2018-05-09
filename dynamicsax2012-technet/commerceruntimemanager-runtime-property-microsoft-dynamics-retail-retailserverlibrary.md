---
title: CommerceRuntimeManager.Runtime Property  (Microsoft.Dynamics.Retail.RetailServerLibrary)
TOCTitle: Runtime Property
ms:assetid: P:Microsoft.Dynamics.Retail.RetailServerLibrary.CommerceRuntimeManager.Runtime
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.retailserverlibrary.commerceruntimemanager.runtime(v=AX.60)
ms:contentKeyID: 62203371
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.CommerceRuntimeManager.Runtime
dev_langs:
- CSharp
- C++
- VB
---

# Runtime Property

Gets the runtime.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary](microsoft-dynamics-retail-retailserverlibrary-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
Public Shared ReadOnly Property Runtime As CommerceRuntime
    Get
'Usage
Dim value As CommerceRuntime

value = CommerceRuntimeManager.Runtime
```

``` csharp
public static CommerceRuntime Runtime { get; }
```

``` c++
public:
static property CommerceRuntime^ Runtime {
    CommerceRuntime^ get ();
}
```

#### Property Value

Type: CommerceRuntime  
Returns CommerceRuntime.  

## See Also

#### Reference

[CommerceRuntimeManager Class](commerceruntimemanager-class-microsoft-dynamics-retail-retailserverlibrary.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary Namespace](microsoft-dynamics-retail-retailserverlibrary-namespace.md)

