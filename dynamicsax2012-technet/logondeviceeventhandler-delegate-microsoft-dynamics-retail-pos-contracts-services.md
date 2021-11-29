---
title: LogOnDeviceEventHandler Delegate (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: LogOnDeviceEventHandler Delegate
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.Services.LogOnDeviceEventHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.logondeviceeventhandler(v=AX.60)
ms:contentKeyID: 49846759
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.LogOnDeviceEventHandler
dev_langs:
- CSharp
- C++
- VB
---

# LogOnDeviceEventHandler Delegate


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Log on device message event handler.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Public Delegate Sub LogOnDeviceEventHandler ( _
    extendedLogOnInfo As IExtendedLogOnInfo _
)
'Usage
Dim instance As New LogOnDeviceEventHandler(AddressOf HandlerMethod)
```

``` csharp
public delegate void LogOnDeviceEventHandler(
    IExtendedLogOnInfo extendedLogOnInfo
)
```

``` c++
public delegate void LogOnDeviceEventHandler(
    IExtendedLogOnInfo^ extendedLogOnInfo
)
```

#### Parameters

  - extendedLogOnInfo  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IExtendedLogOnInfo](iextendedlogoninfo-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

