---
title: TransactionServiceClient.ActivateDevice Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: ActivateDevice Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.ActivateDevice(System.String,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.transactionserviceclient.activatedevice(v=AX.60)
ms:contentKeyID: 62214137
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.ActivateDevice
dev_langs:
- CSharp
- C++
- VB
---

# ActivateDevice Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Activate a device in AX.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Function ActivateDevice ( _
    deviceNumber As String, _
    terminalId As String, _
    staffId As String _
) As DeviceActivationResult
'Usage
Dim instance As TransactionServiceClient
Dim deviceNumber As String
Dim terminalId As String
Dim staffId As String
Dim returnValue As DeviceActivationResult

returnValue = instance.ActivateDevice(deviceNumber, _
    terminalId, staffId)
```

``` csharp
public DeviceActivationResult ActivateDevice(
    string deviceNumber,
    string terminalId,
    string staffId
)
```

``` c++
public:
DeviceActivationResult^ ActivateDevice(
    String^ deviceNumber, 
    String^ terminalId, 
    String^ staffId
)
```

#### Parameters

  - deviceNumber  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - terminalId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - staffId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceActivationResult](deviceactivationresult-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The device information.  

## See Also

#### Reference

[TransactionServiceClient Class](transactionserviceclient-class-microsoft-dynamics-commerce-runtime-transactionservice.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService Namespace](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)

