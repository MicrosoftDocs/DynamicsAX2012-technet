---
title: TransactionServiceClient.DeactivateDevice Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: DeactivateDevice Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.DeactivateDevice(System.String,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.transactionservice.transactionserviceclient.deactivatedevice(v=AX.60)
ms:contentKeyID: 62207933
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.DeactivateDevice
dev_langs:
- CSharp
- C++
- VB
---

# DeactivateDevice Method

Deactivate a device in AX.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Sub DeactivateDevice ( _
    deviceNumber As String, _
    terminalId As String, _
    staffId As String _
)
'Usage
Dim instance As TransactionServiceClient
Dim deviceNumber As String
Dim terminalId As String
Dim staffId As String

instance.DeactivateDevice(deviceNumber, _
    terminalId, staffId)
```

``` csharp
public void DeactivateDevice(
    string deviceNumber,
    string terminalId,
    string staffId
)
```

``` c++
public:
void DeactivateDevice(
    String^ deviceNumber, 
    String^ terminalId, 
    String^ staffId
)
```

#### Parameters

  - deviceNumber  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - terminalId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - staffId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[TransactionServiceClient Class](transactionserviceclient-class-microsoft-dynamics-commerce-runtime-transactionservice.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService Namespace](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)

