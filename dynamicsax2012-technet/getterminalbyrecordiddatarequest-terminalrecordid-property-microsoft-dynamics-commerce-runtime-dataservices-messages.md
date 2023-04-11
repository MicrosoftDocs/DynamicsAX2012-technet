---
title: GetTerminalByRecordIdDataRequest.TerminalRecordId Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: TerminalRecordId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetTerminalByRecordIdDataRequest.TerminalRecordId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getterminalbyrecordiddatarequest.terminalrecordid(v=AX.60)
ms:contentKeyID: 65319334
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetTerminalByRecordIdDataRequest.TerminalRecordId
dev_langs:
- CSharp
- C++
- VB
---

# TerminalRecordId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the terminal record identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property TerminalRecordId As Long
    Get
    Private Set
'Usage
Dim instance As GetTerminalByRecordIdDataRequest
Dim value As Long

value = instance.TerminalRecordId
```

``` csharp
[DataMemberAttribute]
public long TerminalRecordId { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property long long TerminalRecordId {
    long long get ();
    private: void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
The terminal record identifier.  

## See Also

#### Reference

[GetTerminalByRecordIdDataRequest Class](getterminalbyrecordiddatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

