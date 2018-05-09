---
title: IScannerV1.ScannerMessageEvent Event (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: ScannerMessageEvent Event
ms:assetid: E:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IScannerV1.ScannerMessageEvent
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.iscannerv1.scannermessageevent(v=AX.60)
ms:contentKeyID: 47344493
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IScannerV1.ScannerMessageEvent
dev_langs:
- CSharp
- C++
- VB
---

# ScannerMessageEvent Event

Scanner device message event.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Event ScannerMessageEvent As ScannerMessageEventHandler
'Usage
Dim instance As IScannerV1
Dim handler As ScannerMessageEventHandler

AddHandler instance.ScannerMessageEvent, handler
```

``` csharp
event ScannerMessageEventHandler ScannerMessageEvent
```

``` c++
 event ScannerMessageEventHandler^ ScannerMessageEvent {
    void add (ScannerMessageEventHandler^ value);
    void remove (ScannerMessageEventHandler^ value);
}
```

## See Also

#### Reference

[IScannerV1 Interface](iscannerv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

