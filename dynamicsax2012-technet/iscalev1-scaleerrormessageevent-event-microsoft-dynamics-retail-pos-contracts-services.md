---
title: IScaleV1.ScaleErrorMessageEvent Event (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: ScaleErrorMessageEvent Event
ms:assetid: E:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IScaleV1.ScaleErrorMessageEvent
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.iscalev1.scaleerrormessageevent(v=AX.60)
ms:contentKeyID: 47344072
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IScaleV1.ScaleErrorMessageEvent
dev_langs:
- CSharp
- C++
- VB
---

# ScaleErrorMessageEvent Event

Scale device error event.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Event ScaleErrorMessageEvent As ScaleErrorMessageEventHandler
'Usage
Dim instance As IScaleV1
Dim handler As ScaleErrorMessageEventHandler

AddHandler instance.ScaleErrorMessageEvent, handler
```

``` csharp
event ScaleErrorMessageEventHandler ScaleErrorMessageEvent
```

``` c++
 event ScaleErrorMessageEventHandler^ ScaleErrorMessageEvent {
    void add (ScaleErrorMessageEventHandler^ value);
    void remove (ScaleErrorMessageEventHandler^ value);
}
```

## See Also

#### Reference

[IScaleV1 Interface](iscalev1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

