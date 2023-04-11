---
title: InsertAuditLogServiceRequest.Source Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: Source Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.InsertAuditLogServiceRequest.Source
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.insertauditlogservicerequest.source(v=AX.60)
ms:contentKeyID: 65320491
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.InsertAuditLogServiceRequest.Source
dev_langs:
- CSharp
- C++
- VB
---

# Source Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<RequiredAttribute> _
Public Property Source As String
    Get
    Private Set
'Usage
Dim instance As InsertAuditLogServiceRequest
Dim value As String

value = instance.Source
```

``` csharp
[DataMemberAttribute]
[RequiredAttribute]
public string Source { get; private set; }
```

``` c++
[DataMemberAttribute]
[RequiredAttribute]
public:
property String^ Source {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[InsertAuditLogServiceRequest Class](insertauditlogservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

