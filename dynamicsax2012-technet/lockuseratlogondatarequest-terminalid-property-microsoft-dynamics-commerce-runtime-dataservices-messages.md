---
title: LockUserAtLogOnDataRequest.TerminalId Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: TerminalId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.LockUserAtLogOnDataRequest.TerminalId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.lockuseratlogondatarequest.terminalid(v=AX.60)
ms:contentKeyID: 65320878
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.LockUserAtLogOnDataRequest.TerminalId
dev_langs:
- CSharp
- C++
- VB
---

# TerminalId Property

Gets the terminal identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property TerminalId As String
    Get
    Private Set
'Usage
Dim instance As LockUserAtLogOnDataRequest
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
The terminal identifier.  

## See Also

#### Reference

[LockUserAtLogOnDataRequest Class](lockuseratlogondatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

