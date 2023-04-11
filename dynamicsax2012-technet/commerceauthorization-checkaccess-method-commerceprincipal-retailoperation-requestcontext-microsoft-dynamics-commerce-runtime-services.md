---
title: CommerceAuthorization.CheckAccess Method (CommercePrincipal, RetailOperation, RequestContext) (Microsoft.Dynamics.Commerce.Runtime.Services)
TOCTitle: CheckAccess Method (CommercePrincipal, RetailOperation, RequestContext)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.CommerceAuthorization.CheckAccess(Microsoft.Dynamics.Commerce.Runtime.Data.CommercePrincipal,Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailOperation,Microsoft.Dynamics.Commerce.Runtime.RequestContext)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.commerceauthorization.checkaccess(v=AX.60)
ms:contentKeyID: 62208354
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# CheckAccess Method (CommercePrincipal, RetailOperation, RequestContext)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Checks if the principal has permission to do the operation.If not, throws UserAuthorizationException for permission check within workflows.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services](microsoft-dynamics-commerce-runtime-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services (in Microsoft.Dynamics.Commerce.Runtime.Services.dll)

## Syntax

``` vb
'Declaration
Public Shared Sub CheckAccess ( _
    principal As CommercePrincipal, _
    operationId As RetailOperation, _
    context As RequestContext _
)
'Usage
Dim principal As CommercePrincipal
Dim operationId As RetailOperation
Dim context As RequestContext

CommerceAuthorization.CheckAccess(principal, operationId, _
    context)
```

``` csharp
public static void CheckAccess(
    CommercePrincipal principal,
    RetailOperation operationId,
    RequestContext context
)
```

``` c++
public:
static void CheckAccess(
    CommercePrincipal^ principal, 
    RetailOperation operationId, 
    RequestContext^ context
)
```

#### Parameters

  - principal  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.CommercePrincipal](commerceprincipal-class-microsoft-dynamics-commerce-runtime-data.md)  

<!-- end list -->

  - operationId  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailOperation](retailoperation-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - context  
    Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  

## See Also

#### Reference

[CommerceAuthorization Class](commerceauthorization-class-microsoft-dynamics-commerce-runtime-services.md)

[CheckAccess Overload](commerceauthorization-checkaccess-method-microsoft-dynamics-commerce-runtime-services.md)

[Microsoft.Dynamics.Commerce.Runtime.Services Namespace](microsoft-dynamics-commerce-runtime-services-namespace.md)

