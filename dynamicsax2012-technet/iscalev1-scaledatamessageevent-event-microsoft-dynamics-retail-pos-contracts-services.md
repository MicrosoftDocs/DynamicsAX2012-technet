---
title: IScaleV1.ScaleDataMessageEvent Event (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: ScaleDataMessageEvent Event
ms:assetid: E:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IScaleV1.ScaleDataMessageEvent
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iscalev1.scaledatamessageevent(v=AX.60)
ms:contentKeyID: 47343958
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IScaleV1.ScaleDataMessageEvent
dev_langs:
- CSharp
- C++
- VB
---

# ScaleDataMessageEvent Event


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Scale device message event.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Event ScaleDataMessageEvent As ScaleDataMessageEventHandler
'Usage
Dim instance As IScaleV1
Dim handler As ScaleDataMessageEventHandler

AddHandler instance.ScaleDataMessageEvent, handler
```

``` csharp
event ScaleDataMessageEventHandler ScaleDataMessageEvent
```

``` c++
 event ScaleDataMessageEventHandler^ ScaleDataMessageEvent {
    void add (ScaleDataMessageEventHandler^ value);
    void remove (ScaleDataMessageEventHandler^ value);
}
```

## See Also

#### Reference

[IScaleV1 Interface](iscalev1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

