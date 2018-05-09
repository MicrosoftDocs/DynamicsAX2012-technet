---
title: LockUserAtLogOnDataRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: LockUserAtLogOnDataRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.LockUserAtLogOnDataRequest.#ctor(System.Int64,System.String,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.dataservices.messages.lockuseratlogondatarequest.lockuseratlogondatarequest(v=AX.60)
ms:contentKeyID: 65323196
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.LockUserAtLogOnDataRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# LockUserAtLogOnDataRequest Constructor

Initializes a new instance of the [LockUserAtLogOnDataRequest](lockuseratlogondatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    channelId As Long, _
    terminalId As String, _
    staffId As String, _
    dataareaId As String _
)
'Usage
Dim channelId As Long
Dim terminalId As String
Dim staffId As String
Dim dataareaId As String

Dim instance As New LockUserAtLogOnDataRequest(channelId, _
    terminalId, staffId, dataareaId)
```

``` csharp
public LockUserAtLogOnDataRequest(
    long channelId,
    string terminalId,
    string staffId,
    string dataareaId
)
```

``` c++
public:
LockUserAtLogOnDataRequest(
    long long channelId, 
    String^ terminalId, 
    String^ staffId, 
    String^ dataareaId
)
```

#### Parameters

  - channelId  
    Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - terminalId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - staffId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - dataareaId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[LockUserAtLogOnDataRequest Class](lockuseratlogondatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

