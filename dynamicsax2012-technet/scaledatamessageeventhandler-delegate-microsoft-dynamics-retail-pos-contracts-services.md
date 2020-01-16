---
title: ScaleDataMessageEventHandler Delegate (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: ScaleDataMessageEventHandler Delegate
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ScaleDataMessageEventHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.scaledatamessageeventhandler(v=AX.60)
ms:contentKeyID: 47344515
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ScaleDataMessageEventHandler
dev_langs:
- CSharp
- C++
- VB
---

# ScaleDataMessageEventHandler Delegate

The Microsoft.Dynamics.Retail.Pos.Contracts.Services.ScaleDataMessageEventHandler interface is the scale device message event handler delegate.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Public Delegate Sub ScaleDataMessageEventHandler ( _
    weight As Integer _
)
'Usage
Dim instance As New ScaleDataMessageEventHandler(AddressOf HandlerMethod)
```

``` csharp
public delegate void ScaleDataMessageEventHandler(
    int weight
)
```

``` c++
public delegate void ScaleDataMessageEventHandler(
    int weight
)
```

#### Parameters

  - weight  
    Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

