---
title: TransactionServiceClient.AuthenticateDevice Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: AuthenticateDevice Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.AuthenticateDevice(Microsoft.Dynamics.Commerce.Runtime.DataModel.Device@,System.String,System.Int64)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.transactionservice.transactionserviceclient.authenticatedevice(v=AX.60)
ms:contentKeyID: 62207060
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.AuthenticateDevice
dev_langs:
- CSharp
- C++
- VB
---

# AuthenticateDevice Method

Authenticate a device in AX.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Sub AuthenticateDevice ( _
    ByRef device As Device, _
    deviceId As String, _
    terminalRecordId As Long _
)
'Usage
Dim instance As TransactionServiceClient
Dim device As Device
Dim deviceId As String
Dim terminalRecordId As Long

instance.AuthenticateDevice(device, deviceId, _
    terminalRecordId)
```

``` csharp
public void AuthenticateDevice(
    ref Device device,
    string deviceId,
    long terminalRecordId
)
```

``` c++
public:
void AuthenticateDevice(
    Device^% device, 
    String^ deviceId, 
    long long terminalRecordId
)
```

#### Parameters

  - device  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Device](device-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - deviceId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - terminalRecordId  
    Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  

## See Also

#### Reference

[TransactionServiceClient Class](transactionserviceclient-class-microsoft-dynamics-commerce-runtime-transactionservice.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService Namespace](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)

