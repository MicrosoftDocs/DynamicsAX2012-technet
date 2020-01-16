---
title: InsertAuditLogServiceRequest Constructor (String, String, AuditLogTraceLevel, Int32) (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: InsertAuditLogServiceRequest Constructor (String, String, AuditLogTraceLevel, Int32)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.InsertAuditLogServiceRequest.#ctor(System.String,System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.AuditLogTraceLevel,System.Int32)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.insertauditlogservicerequest.insertauditlogservicerequest(v=AX.60)
ms:contentKeyID: 65318046
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# InsertAuditLogServiceRequest Constructor (String, String, AuditLogTraceLevel, Int32)

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    source As String, _
    logEntry As String, _
    logLevel As AuditLogTraceLevel, _
    durationInMilliseconds As Integer _
)
'Usage
Dim source As String
Dim logEntry As String
Dim logLevel As AuditLogTraceLevel
Dim durationInMilliseconds As Integer

Dim instance As New InsertAuditLogServiceRequest(source, _
    logEntry, logLevel, durationInMilliseconds)
```

``` csharp
public InsertAuditLogServiceRequest(
    string source,
    string logEntry,
    AuditLogTraceLevel logLevel,
    int durationInMilliseconds
)
```

``` c++
public:
InsertAuditLogServiceRequest(
    String^ source, 
    String^ logEntry, 
    AuditLogTraceLevel logLevel, 
    int durationInMilliseconds
)
```

#### Parameters

  - source  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - logEntry  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - logLevel  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.AuditLogTraceLevel](auditlogtracelevel-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - durationInMilliseconds  
    Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

## See Also

#### Reference

[InsertAuditLogServiceRequest Class](insertauditlogservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[InsertAuditLogServiceRequest Overload](insertauditlogservicerequest-constructor-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

