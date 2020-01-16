---
title: IRadioFrequencyIDScannerV1.RFIDScannerMessageEvent Event (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: RFIDScannerMessageEvent Event
ms:assetid: E:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IRadioFrequencyIDScannerV1.RFIDScannerMessageEvent
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iradiofrequencyidscannerv1.rfidscannermessageevent(v=AX.60)
ms:contentKeyID: 47344276
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IRadioFrequencyIDScannerV1.RFIDScannerMessageEvent
dev_langs:
- CSharp
- C++
- VB
---

# RFIDScannerMessageEvent Event

Starts a RFID device message event.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Event RFIDScannerMessageEvent As RFIDScannerMessageEventHandler
'Usage
Dim instance As IRadioFrequencyIDScannerV1
Dim handler As RFIDScannerMessageEventHandler

AddHandler instance.RFIDScannerMessageEvent, handler
```

``` csharp
event RFIDScannerMessageEventHandler RFIDScannerMessageEvent
```

``` c++
 event RFIDScannerMessageEventHandler^ RFIDScannerMessageEvent {
    void add (RFIDScannerMessageEventHandler^ value);
    void remove (RFIDScannerMessageEventHandler^ value);
}
```

## See Also

#### Reference

[IRadioFrequencyIDScannerV1 Interface](iradiofrequencyidscannerv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

