---
title: RequestContextExtensions.GetCheckAccessIsManagerAction Method  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: GetCheckAccessIsManagerAction Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.RequestContextExtensions.GetCheckAccessIsManagerAction(Microsoft.Dynamics.Commerce.Runtime.RequestContext)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.requestcontextextensions.getcheckaccessismanageraction(v=AX.60)
ms:contentKeyID: 65319893
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.RequestContextExtensions.GetCheckAccessIsManagerAction
dev_langs:
- CSharp
- C++
- VB
---

# GetCheckAccessIsManagerAction Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the delegate to check if user is manager.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ExtensionAttribute> _
Public Shared Function GetCheckAccessIsManagerAction ( _
    requestContext As RequestContext _
) As Action
'Usage
Dim requestContext As RequestContext
Dim returnValue As Action

returnValue = requestContext.GetCheckAccessIsManagerAction()
```

``` csharp
public static Action GetCheckAccessIsManagerAction(
    this RequestContext requestContext
)
```

``` c++
[ExtensionAttribute]
public:
static Action^ GetCheckAccessIsManagerAction(
    RequestContext^ requestContext
)
```

#### Parameters

  - requestContext  
    Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  

#### Return Value

Type: [System.Action](https://technet.microsoft.com/library/bb534741\(v=ax.60\))  
Instance of [Action](https://technet.microsoft.com/library/bb534741\(v=ax.60\)) from the parameter cache.  

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md). When you use instance method syntax to call this method, omit the first parameter. For more information, see b8020aae-374d-46a9-bcb7-8cc2390b93b6 or 175ce3ff-9bbf-4e64-8421-faeb81a0bb51.

## See Also

#### Reference

[RequestContextExtensions Class](requestcontextextensions-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

