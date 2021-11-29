---
title: InsertAuditLogServiceRequest.DurationInMilliseconds Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: DurationInMilliseconds Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.InsertAuditLogServiceRequest.DurationInMilliseconds
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.insertauditlogservicerequest.durationinmilliseconds(v=AX.60)
ms:contentKeyID: 65319025
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.InsertAuditLogServiceRequest.DurationInMilliseconds
dev_langs:
- CSharp
- C++
- VB
---

# DurationInMilliseconds Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property DurationInMilliseconds As Integer
    Get
    Private Set
'Usage
Dim instance As InsertAuditLogServiceRequest
Dim value As Integer

value = instance.DurationInMilliseconds
```

``` csharp
[DataMemberAttribute]
public int DurationInMilliseconds { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property int DurationInMilliseconds {
    int get ();
    private: void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

## See Also

#### Reference

[InsertAuditLogServiceRequest Class](insertauditlogservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

