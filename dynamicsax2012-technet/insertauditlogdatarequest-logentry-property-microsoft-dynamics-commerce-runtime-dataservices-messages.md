---
title: InsertAuditLogDataRequest.LogEntry Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: LogEntry Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.InsertAuditLogDataRequest.LogEntry
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.insertauditlogdatarequest.logentry(v=AX.60)
ms:contentKeyID: 65317793
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.InsertAuditLogDataRequest.LogEntry
dev_langs:
- CSharp
- C++
- VB
---

# LogEntry Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the log entry.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property LogEntry As String
    Get
    Private Set
'Usage
Dim instance As InsertAuditLogDataRequest
Dim value As String

value = instance.LogEntry
```

``` csharp
[DataMemberAttribute]
public string LogEntry { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ LogEntry {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[InsertAuditLogDataRequest Class](insertauditlogdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

