---
title: CheckAccessServiceRequest Constructor (CommercePrincipal, RetailOperation) (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: CheckAccessServiceRequest Constructor (CommercePrincipal, RetailOperation)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CheckAccessServiceRequest.#ctor(Microsoft.Dynamics.Commerce.Runtime.Data.CommercePrincipal,Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailOperation)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.checkaccessservicerequest.checkaccessservicerequest(v=AX.60)
ms:contentKeyID: 65318099
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# CheckAccessServiceRequest Constructor (CommercePrincipal, RetailOperation)

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    commercePrincipal As CommercePrincipal, _
    operationId As RetailOperation _
)
'Usage
Dim commercePrincipal As CommercePrincipal
Dim operationId As RetailOperation

Dim instance As New CheckAccessServiceRequest(commercePrincipal, _
    operationId)
```

``` csharp
public CheckAccessServiceRequest(
    CommercePrincipal commercePrincipal,
    RetailOperation operationId
)
```

``` c++
public:
CheckAccessServiceRequest(
    CommercePrincipal^ commercePrincipal, 
    RetailOperation operationId
)
```

#### Parameters

  - commercePrincipal  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.CommercePrincipal](commerceprincipal-class-microsoft-dynamics-commerce-runtime-data.md)  

<!-- end list -->

  - operationId  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailOperation](retailoperation-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[CheckAccessServiceRequest Class](checkaccessservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[CheckAccessServiceRequest Overload](checkaccessservicerequest-constructor-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

