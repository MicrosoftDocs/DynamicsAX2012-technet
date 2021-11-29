---
title: PinPadEntryCompleteEventHandler Delegate (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: PinPadEntryCompleteEventHandler Delegate
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.Services.PinPadEntryCompleteEventHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.pinpadentrycompleteeventhandler(v=AX.60)
ms:contentKeyID: 47344295
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.PinPadEntryCompleteEventHandler
dev_langs:
- CSharp
- C++
- VB
---

# PinPadEntryCompleteEventHandler Delegate


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The Microsoft.Dynamics.Retail.Pos.Contracts.Services.PinPadEntryCompleteEventHandler interface is the pinPad device entry complete event handler.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Public Delegate Sub PinPadEntryCompleteEventHandler ( _
    sender As Object, _
    eventArgs As IPinPadInfo _
)
'Usage
Dim instance As New PinPadEntryCompleteEventHandler(AddressOf HandlerMethod)
```

``` csharp
public delegate void PinPadEntryCompleteEventHandler(
    Object sender,
    IPinPadInfo eventArgs
)
```

``` c++
public delegate void PinPadEntryCompleteEventHandler(
    Object^ sender, 
    IPinPadInfo^ eventArgs
)
```

#### Parameters

  - sender  
    Type: [System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  

<!-- end list -->

  - eventArgs  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPinPadInfo](ipinpadinfo-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

