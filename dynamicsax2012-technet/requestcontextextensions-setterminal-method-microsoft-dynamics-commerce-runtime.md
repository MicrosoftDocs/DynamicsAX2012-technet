---
title: RequestContextExtensions.SetTerminal Method  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: SetTerminal Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.RequestContextExtensions.SetTerminal(Microsoft.Dynamics.Commerce.Runtime.RequestContext,Microsoft.Dynamics.Commerce.Runtime.DataModel.Terminal)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.requestcontextextensions.setterminal(v=AX.60)
ms:contentKeyID: 65322187
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.RequestContextExtensions.SetTerminal
dev_langs:
- CSharp
- C++
- VB
---

# SetTerminal Method

Sets the terminal for the current request.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ExtensionAttribute> _
Public Shared Sub SetTerminal ( _
    requestContext As RequestContext, _
    terminal As Terminal _
)
'Usage
Dim requestContext As RequestContext
Dim terminal As Terminal

requestContext.SetTerminal(terminal)
```

``` csharp
public static void SetTerminal(
    this RequestContext requestContext,
    Terminal terminal
)
```

``` c++
[ExtensionAttribute]
public:
static void SetTerminal(
    RequestContext^ requestContext, 
    Terminal^ terminal
)
```

#### Parameters

  - requestContext  
    Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - terminal  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Terminal](terminal-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md). When you use instance method syntax to call this method, omit the first parameter. For more information, see b8020aae-374d-46a9-bcb7-8cc2390b93b6 or 175ce3ff-9bbf-4e64-8421-faeb81a0bb51.

## See Also

#### Reference

[RequestContextExtensions Class](requestcontextextensions-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

