---
title: InsertAuditLogDataRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: InsertAuditLogDataRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.InsertAuditLogDataRequest.#ctor(System.String,System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.AuditLogTraceLevel,System.String,System.String,System.Int32)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.insertauditlogdatarequest.insertauditlogdatarequest(v=AX.60)
ms:contentKeyID: 65320075
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.InsertAuditLogDataRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# InsertAuditLogDataRequest Constructor

Initializes a new instance of the [InsertAuditLogDataRequest](insertauditlogdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    source As String, _
    logEntry As String, _
    logLevel As AuditLogTraceLevel, _
    storeId As String, _
    terminalId As String, _
    durationInMilliseconds As Integer _
)
'Usage
Dim source As String
Dim logEntry As String
Dim logLevel As AuditLogTraceLevel
Dim storeId As String
Dim terminalId As String
Dim durationInMilliseconds As Integer

Dim instance As New InsertAuditLogDataRequest(source, _
    logEntry, logLevel, storeId, terminalId, _
    durationInMilliseconds)
```

``` csharp
public InsertAuditLogDataRequest(
    string source,
    string logEntry,
    AuditLogTraceLevel logLevel,
    string storeId,
    string terminalId,
    int durationInMilliseconds
)
```

``` c++
public:
InsertAuditLogDataRequest(
    String^ source, 
    String^ logEntry, 
    AuditLogTraceLevel logLevel, 
    String^ storeId, 
    String^ terminalId, 
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

  - storeId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - terminalId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - durationInMilliseconds  
    Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

## See Also

#### Reference

[InsertAuditLogDataRequest Class](insertauditlogdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

