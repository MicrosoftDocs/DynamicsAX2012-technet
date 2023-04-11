---
title: RetailServerInstrumentationProvider.RequestEnd Method  (Microsoft.Dynamics.Retail.Tracing.RetailServer)
TOCTitle: RequestEnd Method
ms:assetid: M:Microsoft.Dynamics.Retail.Tracing.RetailServer.RetailServerInstrumentationProvider.RequestEnd(System.String,System.String,System.String,System.Guid)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.tracing.retailserver.retailserverinstrumentationprovider.requestend(v=AX.60)
ms:contentKeyID: 62203831
author: tonyafehr
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Tracing.RetailServer.RetailServerInstrumentationProvider.RequestEnd
dev_langs:
- CSharp
- C++
- VB
---

# RequestEnd Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Occurs when trace event ends.

**Namespace:**  [Microsoft.Dynamics.Retail.Tracing.RetailServer](microsoft-dynamics-retail-tracing-retailserver-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
Public Shared Sub RequestEnd ( _
    message As String, _
    method As String, _
    status As String, _
    correlationId As Guid _
)
'Usage
Dim message As String
Dim method As String
Dim status As String
Dim correlationId As Guid

RetailServerInstrumentationProvider.RequestEnd(message, method, _
    status, correlationId)
```

``` csharp
public static void RequestEnd(
    string message,
    string method,
    string status,
    Guid correlationId
)
```

``` c++
public:
static void RequestEnd(
    String^ message, 
    String^ method, 
    String^ status, 
    Guid correlationId
)
```

#### Parameters

  - message  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - method  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - status  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - correlationId  
    Type: [System.Guid](https://technet.microsoft.com/library/cey1zx63\(v=ax.60\))  

## See Also

#### Reference

[RetailServerInstrumentationProvider Class](retailserverinstrumentationprovider-class-microsoft-dynamics-retail-tracing-retailserver.md)

[Microsoft.Dynamics.Retail.Tracing.RetailServer Namespace](microsoft-dynamics-retail-tracing-retailserver-namespace.md)

