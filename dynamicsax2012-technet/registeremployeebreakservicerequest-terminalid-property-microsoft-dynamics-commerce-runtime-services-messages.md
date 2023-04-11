---
title: RegisterEmployeeBreakServiceRequest.TerminalId Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: TerminalId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.RegisterEmployeeBreakServiceRequest.TerminalId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.registeremployeebreakservicerequest.terminalid(v=AX.60)
ms:contentKeyID: 65322113
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.RegisterEmployeeBreakServiceRequest.TerminalId
dev_langs:
- CSharp
- C++
- VB
---

# TerminalId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property TerminalId As String
    Get
    Private Set
'Usage
Dim instance As RegisterEmployeeBreakServiceRequest
Dim value As String

value = instance.TerminalId
```

``` csharp
[DataMemberAttribute]
public string TerminalId { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ TerminalId {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[RegisterEmployeeBreakServiceRequest Class](registeremployeebreakservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

