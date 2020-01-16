---
title: RetailServerInstrumentationProvider.RequestBegin Method  (Microsoft.Dynamics.Retail.Tracing.RetailServer)
TOCTitle: RequestBegin Method
ms:assetid: M:Microsoft.Dynamics.Retail.Tracing.RetailServer.RetailServerInstrumentationProvider.RequestBegin(System.String,System.String,System.Guid)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.tracing.retailserver.retailserverinstrumentationprovider.requestbegin(v=AX.60)
ms:contentKeyID: 62201929
author: Khairunj
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Tracing.RetailServer.RetailServerInstrumentationProvider.RequestBegin
dev_langs:
- CSharp
- C++
- VB
---

# RequestBegin Method

Occurs when trace event begins.

**Namespace:**  [Microsoft.Dynamics.Retail.Tracing.RetailServer](microsoft-dynamics-retail-tracing-retailserver-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
Public Shared Sub RequestBegin ( _
    message As String, _
    method As String, _
    correlationId As Guid _
)
'Usage
Dim message As String
Dim method As String
Dim correlationId As Guid

RetailServerInstrumentationProvider.RequestBegin(message, method, _
    correlationId)
```

``` csharp
public static void RequestBegin(
    string message,
    string method,
    Guid correlationId
)
```

``` c++
public:
static void RequestBegin(
    String^ message, 
    String^ method, 
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

  - correlationId  
    Type: [System.Guid](https://technet.microsoft.com/library/cey1zx63\(v=ax.60\))  

## See Also

#### Reference

[RetailServerInstrumentationProvider Class](retailserverinstrumentationprovider-class-microsoft-dynamics-retail-tracing-retailserver.md)

[Microsoft.Dynamics.Retail.Tracing.RetailServer Namespace](microsoft-dynamics-retail-tracing-retailserver-namespace.md)

