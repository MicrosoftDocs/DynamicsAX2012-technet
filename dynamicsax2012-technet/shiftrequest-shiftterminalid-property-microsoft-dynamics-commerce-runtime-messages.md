---
title: ShiftRequest.ShiftTerminalId Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: ShiftTerminalId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.ShiftRequest.ShiftTerminalId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.shiftrequest.shiftterminalid(v=AX.60)
ms:contentKeyID: 62211180
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.ShiftRequest.ShiftTerminalId
dev_langs:
- CSharp
- C++
- VB
---

# ShiftTerminalId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the shift terminal identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ShiftTerminalId As String
    Get
    Set
'Usage
Dim instance As ShiftRequest
Dim value As String

value = instance.ShiftTerminalId

instance.ShiftTerminalId = value
```

``` csharp
[DataMemberAttribute]
public string ShiftTerminalId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ ShiftTerminalId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ShiftRequest Class](shiftrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

