---
title: INamedRequestHandler.HandlerName Property  (Microsoft.Dynamics.Commerce.Runtime.Handlers)
TOCTitle: HandlerName Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Handlers.INamedRequestHandler.HandlerName
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.handlers.inamedrequesthandler.handlername(v=AX.60)
ms:contentKeyID: 65320850
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Handlers.INamedRequestHandler.HandlerName
dev_langs:
- CSharp
- C++
- VB
---

# HandlerName Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the unique name for this request handler.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Handlers](microsoft-dynamics-commerce-runtime-handlers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property HandlerName As String
    Get
'Usage
Dim instance As INamedRequestHandler
Dim value As String

value = instance.HandlerName
```

``` csharp
string HandlerName { get; }
```

``` c++
property String^ HandlerName {
    String^ get ();
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[INamedRequestHandler Interface](inamedrequesthandler-interface-microsoft-dynamics-commerce-runtime-handlers.md)

[Microsoft.Dynamics.Commerce.Runtime.Handlers Namespace](microsoft-dynamics-commerce-runtime-handlers-namespace.md)

