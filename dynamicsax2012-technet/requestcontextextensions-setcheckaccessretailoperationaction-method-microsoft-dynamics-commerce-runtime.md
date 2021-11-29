---
title: RequestContextExtensions.SetCheckAccessRetailOperationAction Method  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: SetCheckAccessRetailOperationAction Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.RequestContextExtensions.SetCheckAccessRetailOperationAction(Microsoft.Dynamics.Commerce.Runtime.RequestContext,System.Action{Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailOperation})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.requestcontextextensions.setcheckaccessretailoperationaction(v=AX.60)
ms:contentKeyID: 65319750
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.RequestContextExtensions.SetCheckAccessRetailOperationAction
dev_langs:
- CSharp
- C++
- VB
---

# SetCheckAccessRetailOperationAction Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Sets the delegate to check access for [RetailOperation](retailoperation-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ExtensionAttribute> _
Public Shared Sub SetCheckAccessRetailOperationAction ( _
    requestContext As RequestContext, _
    checkAccessRetailOperation As Action(Of RetailOperation) _
)
'Usage
Dim requestContext As RequestContext
Dim checkAccessRetailOperation As Action(Of RetailOperation)

requestContext.SetCheckAccessRetailOperationAction(checkAccessRetailOperation)
```

``` csharp
public static void SetCheckAccessRetailOperationAction(
    this RequestContext requestContext,
    Action<RetailOperation> checkAccessRetailOperation
)
```

``` c++
[ExtensionAttribute]
public:
static void SetCheckAccessRetailOperationAction(
    RequestContext^ requestContext, 
    Action<RetailOperation>^ checkAccessRetailOperation
)
```

#### Parameters

  - requestContext  
    Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - checkAccessRetailOperation  
    Type: [System.Action](https://technet.microsoft.com/library/018hxwa8\(v=ax.60\))\<[RetailOperation](retailoperation-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md). When you use instance method syntax to call this method, omit the first parameter. For more information, see b8020aae-374d-46a9-bcb7-8cc2390b93b6 or 175ce3ff-9bbf-4e64-8421-faeb81a0bb51.

## See Also

#### Reference

[RequestContextExtensions Class](requestcontextextensions-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

