---
title: MSRMessageEventHandler Delegate (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: MSRMessageEventHandler Delegate
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.Services.MSRMessageEventHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.msrmessageeventhandler(v=AX.60)
ms:contentKeyID: 47344461
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.MSRMessageEventHandler
dev_langs:
- CSharp
- C++
- VB
---

# MSRMessageEventHandler Delegate


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The Microsoft.Dynamics.Retail.Pos.Contracts.Services.MSRMessageEventHandler interface is the MSR device message event handler.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Public Delegate Sub MSRMessageEventHandler ( _
    cardInfo As ICardInfo _
)
'Usage
Dim instance As New MSRMessageEventHandler(AddressOf HandlerMethod)
```

``` csharp
public delegate void MSRMessageEventHandler(
    ICardInfo cardInfo
)
```

``` c++
public delegate void MSRMessageEventHandler(
    ICardInfo^ cardInfo
)
```

#### Parameters

  - cardInfo  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICardInfo](icardinfo-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

