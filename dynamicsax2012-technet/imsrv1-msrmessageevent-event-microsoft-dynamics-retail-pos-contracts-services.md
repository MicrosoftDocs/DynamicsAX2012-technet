---
title: IMSRV1.MSRMessageEvent Event (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: MSRMessageEvent Event
ms:assetid: E:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IMSRV1.MSRMessageEvent
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.imsrv1.msrmessageevent(v=AX.60)
ms:contentKeyID: 47344219
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IMSRV1.MSRMessageEvent
dev_langs:
- CSharp
- C++
- VB
---

# MSRMessageEvent Event

MSR device message event.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Event MSRMessageEvent As MSRMessageEventHandler
'Usage
Dim instance As IMSRV1
Dim handler As MSRMessageEventHandler

AddHandler instance.MSRMessageEvent, handler
```

``` csharp
event MSRMessageEventHandler MSRMessageEvent
```

``` c++
 event MSRMessageEventHandler^ MSRMessageEvent {
    void add (MSRMessageEventHandler^ value);
    void remove (MSRMessageEventHandler^ value);
}
```

## See Also

#### Reference

[IMSRV1 Interface](imsrv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

