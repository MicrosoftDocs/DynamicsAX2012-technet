---
title: ICashDrawerV1.CashDrawerMessageEvent Event (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: CashDrawerMessageEvent Event
ms:assetid: E:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICashDrawerV1.CashDrawerMessageEvent
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.icashdrawerv1.cashdrawermessageevent(v=AX.60)
ms:contentKeyID: 47344180
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICashDrawerV1.CashDrawerMessageEvent
dev_langs:
- CSharp
- C++
- VB
---

# CashDrawerMessageEvent Event


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Runs the cash drawer message event.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Event CashDrawerMessageEvent As CashDrawerMessageEventHandler
'Usage
Dim instance As ICashDrawerV1
Dim handler As CashDrawerMessageEventHandler

AddHandler instance.CashDrawerMessageEvent, handler
```

``` csharp
event CashDrawerMessageEventHandler CashDrawerMessageEvent
```

``` c++
 event CashDrawerMessageEventHandler^ CashDrawerMessageEvent {
    void add (CashDrawerMessageEventHandler^ value);
    void remove (CashDrawerMessageEventHandler^ value);
}
```

## See Also

#### Reference

[ICashDrawerV1 Interface](icashdrawerv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

