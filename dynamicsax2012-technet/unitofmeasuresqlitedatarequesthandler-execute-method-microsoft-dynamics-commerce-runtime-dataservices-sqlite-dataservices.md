---
title: UnitOfMeasureSqliteDataRequestHandler.Execute Method  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite.DataServices)
TOCTitle: Execute Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite.DataServices.UnitOfMeasureSqliteDataRequestHandler.Execute(Microsoft.Dynamics.Commerce.Runtime.Messages.Request)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.sqlite.dataservices.unitofmeasuresqlitedatarequesthandler.execute(v=AX.60)
ms:contentKeyID: 65321436
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite.DataServices.UnitOfMeasureSqliteDataRequestHandler.Execute
dev_langs:
- CSharp
- C++
- VB
---

# Execute Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite.DataServices](microsoft-dynamics-commerce-runtime-dataservices-sqlite-dataservices-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite.dll)

## Syntax

``` vb
'Declaration
Public Function Execute ( _
    request As Request _
) As Response
'Usage
Dim instance As UnitOfMeasureSqliteDataRequestHandler
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

#### Implements

[IRequestHandler.Execute(Request)](irequesthandler-execute-method-microsoft-dynamics-commerce-runtime-workflow.md)  

## See Also

#### Reference

[UnitOfMeasureSqliteDataRequestHandler Class](unitofmeasuresqlitedatarequesthandler-class-microsoft-dynamics-commerce-runtime-dataservices-sqlite-dataservices.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite.DataServices Namespace](microsoft-dynamics-commerce-runtime-dataservices-sqlite-dataservices-namespace.md)

