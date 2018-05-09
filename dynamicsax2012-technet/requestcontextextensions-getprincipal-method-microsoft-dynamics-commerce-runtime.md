---
title: RequestContextExtensions.GetPrincipal Method  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: GetPrincipal Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.RequestContextExtensions.GetPrincipal(Microsoft.Dynamics.Commerce.Runtime.RequestContext)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.requestcontextextensions.getprincipal(v=AX.60)
ms:contentKeyID: 65315592
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.RequestContextExtensions.GetPrincipal
dev_langs:
- CSharp
- C++
- VB
---

# GetPrincipal Method

Gets the principal for the request.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ExtensionAttribute> _
Public Shared Function GetPrincipal ( _
    requestContext As RequestContext _
) As CommercePrincipal
'Usage
Dim requestContext As RequestContext
Dim returnValue As CommercePrincipal

returnValue = requestContext.GetPrincipal()
```

``` csharp
public static CommercePrincipal GetPrincipal(
    this RequestContext requestContext
)
```

``` c++
[ExtensionAttribute]
public:
static CommercePrincipal^ GetPrincipal(
    RequestContext^ requestContext
)
```

#### Parameters

  - requestContext  
    Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Data.CommercePrincipal](commerceprincipal-class-microsoft-dynamics-commerce-runtime-data.md)  
Instance of [CommercePrincipal](commerceprincipal-class-microsoft-dynamics-commerce-runtime-data.md) from the parameter cache.  

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md). When you use instance method syntax to call this method, omit the first parameter. For more information, see b8020aae-374d-46a9-bcb7-8cc2390b93b6 or 175ce3ff-9bbf-4e64-8421-faeb81a0bb51.

## See Also

#### Reference

[RequestContextExtensions Class](requestcontextextensions-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

