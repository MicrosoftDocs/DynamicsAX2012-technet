---
title: CashDrawerMessageEventHandler Delegate (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: CashDrawerMessageEventHandler Delegate
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.Services.CashDrawerMessageEventHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.cashdrawermessageeventhandler(v=AX.60)
ms:contentKeyID: 47344302
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.CashDrawerMessageEventHandler
dev_langs:
- CSharp
- C++
- VB
---

# CashDrawerMessageEventHandler Delegate

The Microsoft.Dynamics.Retail.Pos.Contracts.Services.CashDrawerMessageEventHandler interface is the cash drawer device message event handler class.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Public Delegate Sub CashDrawerMessageEventHandler ( _
    message As String _
)
'Usage
Dim instance As New CashDrawerMessageEventHandler(AddressOf HandlerMethod)
```

``` csharp
public delegate void CashDrawerMessageEventHandler(
    string message
)
```

``` c++
public delegate void CashDrawerMessageEventHandler(
    String^ message
)
```

#### Parameters

  - message  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

