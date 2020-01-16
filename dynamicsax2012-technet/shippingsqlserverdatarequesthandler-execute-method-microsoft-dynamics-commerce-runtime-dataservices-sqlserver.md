---
title: ShippingSqlServerDataRequestHandler.Execute Method  (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer)
TOCTitle: Execute Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.ShippingSqlServerDataRequestHandler.Execute(Microsoft.Dynamics.Commerce.Runtime.Messages.Request)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.sqlserver.shippingsqlserverdatarequesthandler.execute(v=AX.60)
ms:contentKeyID: 65316461
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.ShippingSqlServerDataRequestHandler.Execute
dev_langs:
- CSharp
- C++
- VB
---

# Execute Method

Entry point to tax data service of the request execution.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer](microsoft-dynamics-commerce-runtime-dataservices-sqlserver-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer (in Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)

## Syntax

``` vb
'Declaration
Public Function Execute ( _
    request As Request _
) As Response
'Usage
Dim instance As ShippingSqlServerDataRequestHandler
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
Result of executing request, or null object for void operations.  

#### Implements

[IRequestHandler.Execute(Request)](irequesthandler-execute-method-microsoft-dynamics-commerce-runtime-workflow.md)  

## See Also

#### Reference

[ShippingSqlServerDataRequestHandler Class](shippingsqlserverdatarequesthandler-class-microsoft-dynamics-commerce-runtime-dataservices-sqlserver.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer Namespace](microsoft-dynamics-commerce-runtime-dataservices-sqlserver-namespace.md)

