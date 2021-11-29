---
title: ICashChangerV1.LevelStatusEvent Event (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: LevelStatusEvent Event
ms:assetid: E:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICashChangerV1.LevelStatusEvent
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.icashchangerv1.levelstatusevent(v=AX.60)
ms:contentKeyID: 47344446
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICashChangerV1.LevelStatusEvent
dev_langs:
- CSharp
- C++
- VB
---

# LevelStatusEvent Event


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Runs level status event.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Event LevelStatusEvent As LevelStatusDelegate
'Usage
Dim instance As ICashChangerV1
Dim handler As LevelStatusDelegate

AddHandler instance.LevelStatusEvent, handler
```

``` csharp
event LevelStatusDelegate LevelStatusEvent
```

``` c++
 event LevelStatusDelegate^ LevelStatusEvent {
    void add (LevelStatusDelegate^ value);
    void remove (LevelStatusDelegate^ value);
}
```

## See Also

#### Reference

[ICashChangerV1 Interface](icashchangerv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

