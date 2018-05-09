---
title: IPinPadV1.EntryCompleteEvent Event (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: EntryCompleteEvent Event
ms:assetid: E:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPinPadV1.EntryCompleteEvent
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.ipinpadv1.entrycompleteevent(v=AX.60)
ms:contentKeyID: 47343976
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPinPadV1.EntryCompleteEvent
dev_langs:
- CSharp
- C++
- VB
---

# EntryCompleteEvent Event

Tries PinPad entry complete event.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Event EntryCompleteEvent As PinPadEntryCompleteEventHandler
'Usage
Dim instance As IPinPadV1
Dim handler As PinPadEntryCompleteEventHandler

AddHandler instance.EntryCompleteEvent, handler
```

``` csharp
event PinPadEntryCompleteEventHandler EntryCompleteEvent
```

``` c++
 event PinPadEntryCompleteEventHandler^ EntryCompleteEvent {
    void add (PinPadEntryCompleteEventHandler^ value);
    void remove (PinPadEntryCompleteEventHandler^ value);
}
```

## See Also

#### Reference

[IPinPadV1 Interface](ipinpadv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

