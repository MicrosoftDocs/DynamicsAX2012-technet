---
title: CommerceAuthorization.CheckAccess Method (CommercePrincipal, RetailOperation, RequestContext, Boolean) (Microsoft.Dynamics.Commerce.Runtime.Services)
TOCTitle: CheckAccess Method (CommercePrincipal, RetailOperation, RequestContext, Boolean)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.CommerceAuthorization.CheckAccess(Microsoft.Dynamics.Commerce.Runtime.Data.CommercePrincipal,Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailOperation,Microsoft.Dynamics.Commerce.Runtime.RequestContext,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.commerceauthorization.checkaccess(v=AX.60)
ms:contentKeyID: 62212146
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# CheckAccess Method (CommercePrincipal, RetailOperation, RequestContext, Boolean)

Checks if the principal has permission to do the operation.If not, throws UserAuthorizationException for permission check within workflows.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services](microsoft-dynamics-commerce-runtime-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services (in Microsoft.Dynamics.Commerce.Runtime.Services.dll)

## Syntax

``` vb
'Declaration
Public Shared Sub CheckAccess ( _
    principal As CommercePrincipal, _
    operationId As RetailOperation, _
    context As RequestContext, _
    nonDrawerOperationCheckRequired As Boolean _
)
'Usage
Dim principal As CommercePrincipal
Dim operationId As RetailOperation
Dim context As RequestContext
Dim nonDrawerOperationCheckRequired As Boolean

CommerceAuthorization.CheckAccess(principal, operationId, _
    context, nonDrawerOperationCheckRequired)
```

``` csharp
public static void CheckAccess(
    CommercePrincipal principal,
    RetailOperation operationId,
    RequestContext context,
    bool nonDrawerOperationCheckRequired
)
```

``` c++
public:
static void CheckAccess(
    CommercePrincipal^ principal, 
    RetailOperation operationId, 
    RequestContext^ context, 
    bool nonDrawerOperationCheckRequired
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

<!-- end list -->

  - nonDrawerOperationCheckRequired  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[CommerceAuthorization Class](commerceauthorization-class-microsoft-dynamics-commerce-runtime-services.md)

[CheckAccess Overload](commerceauthorization-checkaccess-method-microsoft-dynamics-commerce-runtime-services.md)

[Microsoft.Dynamics.Commerce.Runtime.Services Namespace](microsoft-dynamics-commerce-runtime-services-namespace.md)

