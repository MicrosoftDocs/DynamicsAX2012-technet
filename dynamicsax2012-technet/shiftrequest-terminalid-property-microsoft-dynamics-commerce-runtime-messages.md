---
title: ShiftRequest.TerminalId Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: TerminalId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.ShiftRequest.TerminalId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.shiftrequest.terminalid(v=AX.60)
ms:contentKeyID: 65322362
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.ShiftRequest.TerminalId
dev_langs:
- CSharp
- C++
- VB
---

# TerminalId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property TerminalId As String
    Get
    Set
'Usage
Dim instance As ShiftRequest
Dim value As String

value = instance.TerminalId

instance.TerminalId = value
```

``` csharp
[DataMemberAttribute]
public string TerminalId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ TerminalId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[ShiftRequest Class](shiftrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

