---
title: ScaleErrorMessageEventHandler Delegate (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: ScaleErrorMessageEventHandler Delegate
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ScaleErrorMessageEventHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.scaleerrormessageeventhandler(v=AX.60)
ms:contentKeyID: 47344391
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ScaleErrorMessageEventHandler
dev_langs:
- CSharp
- C++
- VB
---

# ScaleErrorMessageEventHandler Delegate

Scale device error message handler delegate.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Public Delegate Sub ScaleErrorMessageEventHandler ( _
    message As String _
)
'Usage
Dim instance As New ScaleErrorMessageEventHandler(AddressOf HandlerMethod)
```

``` csharp
public delegate void ScaleErrorMessageEventHandler(
    string message
)
```

``` c++
public delegate void ScaleErrorMessageEventHandler(
    String^ message
)
```

#### Parameters

  - message  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

