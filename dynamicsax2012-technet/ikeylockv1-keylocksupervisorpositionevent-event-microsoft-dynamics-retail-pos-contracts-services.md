---
title: IKeyLockV1.KeyLockSupervisorPositionEvent Event (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: KeyLockSupervisorPositionEvent Event
ms:assetid: E:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IKeyLockV1.KeyLockSupervisorPositionEvent
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.ikeylockv1.keylocksupervisorpositionevent(v=AX.60)
ms:contentKeyID: 47344140
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IKeyLockV1.KeyLockSupervisorPositionEvent
dev_langs:
- CSharp
- C++
- VB
---

# KeyLockSupervisorPositionEvent Event

KeyLock state change event.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Event KeyLockSupervisorPositionEvent As KeyLockSupervisorPositionEventHandler
'Usage
Dim instance As IKeyLockV1
Dim handler As KeyLockSupervisorPositionEventHandler

AddHandler instance.KeyLockSupervisorPositionEvent, handler
```

``` csharp
event KeyLockSupervisorPositionEventHandler KeyLockSupervisorPositionEvent
```

``` c++
 event KeyLockSupervisorPositionEventHandler^ KeyLockSupervisorPositionEvent {
    void add (KeyLockSupervisorPositionEventHandler^ value);
    void remove (KeyLockSupervisorPositionEventHandler^ value);
}
```

## See Also

#### Reference

[IKeyLockV1 Interface](ikeylockv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

