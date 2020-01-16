---
title: TillLayoutDataRequestHandler.Execute Method  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Common)
TOCTitle: Execute Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.TillLayoutDataRequestHandler.Execute(Microsoft.Dynamics.Commerce.Runtime.Messages.Request)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.common.tilllayoutdatarequesthandler.execute(v=AX.60)
ms:contentKeyID: 65318408
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Common.TillLayoutDataRequestHandler.Execute
dev_langs:
- CSharp
- C++
- VB
---

# Execute Method

Represents the entry point of the request handler.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Common](microsoft-dynamics-commerce-runtime-dataservices-common-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices (in Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)

## Syntax

``` vb
'Declaration
Public Function Execute ( _
    request As Request _
) As Response
'Usage
Dim instance As TillLayoutDataRequestHandler
Dim request As Request
Dim returnValue As Response

returnValue = instance.Execute(request)
```

``` csharp
public Response Execute(
    Request request
)
```

``` c++
public:
virtual Response^ Execute(
    Request^ request
) sealed
```

#### Parameters

  - request  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Messages.Request](request-class-microsoft-dynamics-commerce-runtime-messages.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Messages.Response](response-class-microsoft-dynamics-commerce-runtime-messages.md)  
The outgoing response message.  

#### Implements

[IRequestHandler.Execute(Request)](irequesthandler-execute-method-microsoft-dynamics-commerce-runtime-workflow.md)  

## See Also

#### Reference

[TillLayoutDataRequestHandler Class](tilllayoutdatarequesthandler-class-microsoft-dynamics-commerce-runtime-dataservices-common.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Common Namespace](microsoft-dynamics-commerce-runtime-dataservices-common-namespace.md)

