---
title: StockCountDataRequestHandler.Execute Method  (Microsoft.Dynamics.Commerce.Runtime.DataServices)
TOCTitle: Execute Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.StockCountDataRequestHandler.Execute(Microsoft.Dynamics.Commerce.Runtime.Messages.Request)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.stockcountdatarequesthandler.execute(v=AX.60)
ms:contentKeyID: 65322608
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.StockCountDataRequestHandler.Execute
dev_langs:
- CSharp
- C++
- VB
---

# Execute Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Represents the entry point of the request handler.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices](microsoft-dynamics-commerce-runtime-dataservices-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices (in Microsoft.Dynamics.Commerce.Runtime.DataServices.dll)

## Syntax

``` vb
'Declaration
Public Function Execute ( _
    request As Request _
) As Response
'Usage
Dim instance As StockCountDataRequestHandler
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

[StockCountDataRequestHandler Class](stockcountdatarequesthandler-class-microsoft-dynamics-commerce-runtime-dataservices.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices Namespace](microsoft-dynamics-commerce-runtime-dataservices-namespace.md)

