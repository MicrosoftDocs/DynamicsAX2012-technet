---
title: SalesTransactionSqlServerDataRequestHandler.Execute Method  (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.DataServices)
TOCTitle: Execute Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.DataServices.SalesTransactionSqlServerDataRequestHandler.Execute(Microsoft.Dynamics.Commerce.Runtime.Messages.Request)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.sqlserver.dataservices.salestransactionsqlserverdatarequesthandler.execute(v=AX.60)
ms:contentKeyID: 65316699
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.DataServices.SalesTransactionSqlServerDataRequestHandler.Execute
dev_langs:
- CSharp
- C++
- VB
---

# Execute Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the sales transaction to be saved.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.DataServices](microsoft-dynamics-commerce-runtime-dataservices-sqlserver-dataservices-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer (in Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)

## Syntax

``` vb
'Declaration
Public Function Execute ( _
    request As Request _
) As Response
'Usage
Dim instance As SalesTransactionSqlServerDataRequestHandler
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
The response message.  

#### Implements

[IRequestHandler.Execute(Request)](irequesthandler-execute-method-microsoft-dynamics-commerce-runtime-workflow.md)  

## See Also

#### Reference

[SalesTransactionSqlServerDataRequestHandler Class](salestransactionsqlserverdatarequesthandler-class-microsoft-dynamics-commerce-runtime-dataservices-sqlserver-dataservices.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.DataServices Namespace](microsoft-dynamics-commerce-runtime-dataservices-sqlserver-dataservices-namespace.md)

