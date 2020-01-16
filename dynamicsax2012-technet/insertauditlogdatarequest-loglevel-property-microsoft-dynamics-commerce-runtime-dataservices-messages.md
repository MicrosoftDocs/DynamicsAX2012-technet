---
title: InsertAuditLogDataRequest.LogLevel Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: LogLevel Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.InsertAuditLogDataRequest.LogLevel
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.insertauditlogdatarequest.loglevel(v=AX.60)
ms:contentKeyID: 65320263
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.InsertAuditLogDataRequest.LogLevel
dev_langs:
- CSharp
- C++
- VB
---

# LogLevel Property

Gets the log level.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property LogLevel As AuditLogTraceLevel
    Get
    Private Set
'Usage
Dim instance As InsertAuditLogDataRequest
Dim value As AuditLogTraceLevel

value = instance.LogLevel
```

``` csharp
[DataMemberAttribute]
public AuditLogTraceLevel LogLevel { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property AuditLogTraceLevel LogLevel {
    AuditLogTraceLevel get ();
    private: void set (AuditLogTraceLevel value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.AuditLogTraceLevel](auditlogtracelevel-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [AuditLogTraceLevel](auditlogtracelevel-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[InsertAuditLogDataRequest Class](insertauditlogdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

