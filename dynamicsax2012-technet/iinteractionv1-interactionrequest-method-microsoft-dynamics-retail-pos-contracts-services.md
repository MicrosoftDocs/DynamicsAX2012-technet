---
title: IInteractionV1.InteractionRequest Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: InteractionRequest Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IInteractionV1.InteractionRequest(Microsoft.Practices.Prism.Interactivity.InteractionRequest.InteractionRequestedEventArgs)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iinteractionv1.interactionrequest(v=AX.60)
ms:contentKeyID: 49853754
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IInteractionV1.InteractionRequest
dev_langs:
- CSharp
- C++
- VB
---

# InteractionRequest Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Method called to process an interation.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub InteractionRequest ( _
    e As InteractionRequestedEventArgs _
)
'Usage
Dim instance As IInteractionV1
Dim e As InteractionRequestedEventArgs

instance.InteractionRequest(e)
```

``` csharp
void InteractionRequest(
    InteractionRequestedEventArgs e
)
```

``` c++
void InteractionRequest(
    InteractionRequestedEventArgs^ e
)
```

#### Parameters

  - e  
    Type: InteractionRequestedEventArgs  

## See Also

#### Reference

[IInteractionV1 Interface](iinteractionv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

