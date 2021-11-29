---
title: ICashChangerV1.ErrorEvent Event (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: ErrorEvent Event
ms:assetid: E:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICashChangerV1.ErrorEvent
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.icashchangerv1.errorevent(v=AX.60)
ms:contentKeyID: 47344335
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICashChangerV1.ErrorEvent
dev_langs:
- CSharp
- C++
- VB
---

# ErrorEvent Event


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initiates an Error event.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Event ErrorEvent As ErrorEventDelegate
'Usage
Dim instance As ICashChangerV1
Dim handler As ErrorEventDelegate

AddHandler instance.ErrorEvent, handler
```

``` csharp
event ErrorEventDelegate ErrorEvent
```

``` c++
 event ErrorEventDelegate^ ErrorEvent {
    void add (ErrorEventDelegate^ value);
    void remove (ErrorEventDelegate^ value);
}
```

## See Also

#### Reference

[ICashChangerV1 Interface](icashchangerv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

