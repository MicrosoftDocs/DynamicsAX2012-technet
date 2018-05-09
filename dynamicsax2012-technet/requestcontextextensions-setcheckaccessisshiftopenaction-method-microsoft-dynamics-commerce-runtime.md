---
title: RequestContextExtensions.SetCheckAccessIsShiftOpenAction Method  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: SetCheckAccessIsShiftOpenAction Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.RequestContextExtensions.SetCheckAccessIsShiftOpenAction(Microsoft.Dynamics.Commerce.Runtime.RequestContext,System.Action)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.requestcontextextensions.setcheckaccessisshiftopenaction(v=AX.60)
ms:contentKeyID: 65320895
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.RequestContextExtensions.SetCheckAccessIsShiftOpenAction
dev_langs:
- CSharp
- C++
- VB
---

# SetCheckAccessIsShiftOpenAction Method

Sets the delegate to check if user has an open shift.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ExtensionAttribute> _
Public Shared Sub SetCheckAccessIsShiftOpenAction ( _
    requestContext As RequestContext, _
    checkAccessIsShiftOpen As Action _
)
'Usage
Dim requestContext As RequestContext
Dim checkAccessIsShiftOpen As Action

requestContext.SetCheckAccessIsShiftOpenAction(checkAccessIsShiftOpen)
```

``` csharp
public static void SetCheckAccessIsShiftOpenAction(
    this RequestContext requestContext,
    Action checkAccessIsShiftOpen
)
```

``` c++
[ExtensionAttribute]
public:
static void SetCheckAccessIsShiftOpenAction(
    RequestContext^ requestContext, 
    Action^ checkAccessIsShiftOpen
)
```

#### Parameters

  - requestContext  
    Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - checkAccessIsShiftOpen  
    Type: [System.Action](https://technet.microsoft.com/en-us/library/bb534741\(v=ax.60\))  

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md). When you use instance method syntax to call this method, omit the first parameter. For more information, see b8020aae-374d-46a9-bcb7-8cc2390b93b6 or 175ce3ff-9bbf-4e64-8421-faeb81a0bb51.

## See Also

#### Reference

[RequestContextExtensions Class](requestcontextextensions-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

