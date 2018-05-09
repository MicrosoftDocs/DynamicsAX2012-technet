---
title: RequestContextExtensions.SetPrincipal Method  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: SetPrincipal Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.RequestContextExtensions.SetPrincipal(Microsoft.Dynamics.Commerce.Runtime.RequestContext,Microsoft.Dynamics.Commerce.Runtime.Data.CommercePrincipal)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.requestcontextextensions.setprincipal(v=AX.60)
ms:contentKeyID: 65321270
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.RequestContextExtensions.SetPrincipal
dev_langs:
- CSharp
- C++
- VB
---

# SetPrincipal Method

Sets the principal for the request.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ExtensionAttribute> _
Public Shared Sub SetPrincipal ( _
    requestContext As RequestContext, _
    principal As CommercePrincipal _
)
'Usage
Dim requestContext As RequestContext
Dim principal As CommercePrincipal

requestContext.SetPrincipal(principal)
```

``` csharp
public static void SetPrincipal(
    this RequestContext requestContext,
    CommercePrincipal principal
)
```

``` c++
[ExtensionAttribute]
public:
static void SetPrincipal(
    RequestContext^ requestContext, 
    CommercePrincipal^ principal
)
```

#### Parameters

  - requestContext  
    Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - principal  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.CommercePrincipal](commerceprincipal-class-microsoft-dynamics-commerce-runtime-data.md)  

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md). When you use instance method syntax to call this method, omit the first parameter. For more information, see b8020aae-374d-46a9-bcb7-8cc2390b93b6 or 175ce3ff-9bbf-4e64-8421-faeb81a0bb51.

## See Also

#### Reference

[RequestContextExtensions Class](requestcontextextensions-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

