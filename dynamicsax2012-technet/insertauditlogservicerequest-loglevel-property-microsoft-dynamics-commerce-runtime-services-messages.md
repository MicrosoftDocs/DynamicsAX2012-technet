---
title: InsertAuditLogServiceRequest.LogLevel Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: LogLevel Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.InsertAuditLogServiceRequest.LogLevel
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.insertauditlogservicerequest.loglevel(v=AX.60)
ms:contentKeyID: 65317304
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.InsertAuditLogServiceRequest.LogLevel
dev_langs:
- CSharp
- C++
- VB
---

# LogLevel Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property LogLevel As AuditLogTraceLevel
    Get
    Private Set
'Usage
Dim instance As InsertAuditLogServiceRequest
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

## See Also

#### Reference

[InsertAuditLogServiceRequest Class](insertauditlogservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

