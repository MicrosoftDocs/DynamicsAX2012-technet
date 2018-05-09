---
title: UnLockUserAtLogOffDataRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: UnLockUserAtLogOffDataRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.UnLockUserAtLogOffDataRequest.#ctor(System.Int64,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.dataservices.messages.unlockuseratlogoffdatarequest.unlockuseratlogoffdatarequest(v=AX.60)
ms:contentKeyID: 65319139
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.UnLockUserAtLogOffDataRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# UnLockUserAtLogOffDataRequest Constructor

Initializes a new instance of the [UnLockUserAtLogOffDataRequest](unlockuseratlogoffdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    channelId As Long, _
    staffId As String, _
    dataareaId As String _
)
'Usage
Dim channelId As Long
Dim staffId As String
Dim dataareaId As String

Dim instance As New UnLockUserAtLogOffDataRequest(channelId, _
    staffId, dataareaId)
```

``` csharp
public UnLockUserAtLogOffDataRequest(
    long channelId,
    string staffId,
    string dataareaId
)
```

``` c++
public:
UnLockUserAtLogOffDataRequest(
    long long channelId, 
    String^ staffId, 
    String^ dataareaId
)
```

#### Parameters

  - channelId  
    Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - staffId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - dataareaId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[UnLockUserAtLogOffDataRequest Class](unlockuseratlogoffdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

