---
title: RFIDScannerMessageEventHandler Delegate (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: RFIDScannerMessageEventHandler Delegate
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.Services.RFIDScannerMessageEventHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.rfidscannermessageeventhandler(v=AX.60)
ms:contentKeyID: 47344424
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.RFIDScannerMessageEventHandler
dev_langs:
- CSharp
- C++
- VB
---

# RFIDScannerMessageEventHandler Delegate


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The Microsoft.Dynamics.Retail.Pos.Contracts.Services.RFIDScannerMessageEventHandler interface is the RFID device message event handler.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Public Delegate Sub RFIDScannerMessageEventHandler
'Usage
Dim instance As New RFIDScannerMessageEventHandler(AddressOf HandlerMethod)
```

``` csharp
public delegate void RFIDScannerMessageEventHandler()
```

``` c++
public delegate void RFIDScannerMessageEventHandler()
```

## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

