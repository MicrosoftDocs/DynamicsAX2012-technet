---
title: ScannerMessageEventHandler Delegate (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: ScannerMessageEventHandler Delegate
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ScannerMessageEventHandler
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.scannermessageeventhandler(v=AX.60)
ms:contentKeyID: 47344474
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ScannerMessageEventHandler
dev_langs:
- CSharp
- C++
- VB
---

# ScannerMessageEventHandler Delegate

Scanner device message event handler.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Public Delegate Sub ScannerMessageEventHandler ( _
    scanInfo As IScanInfo _
)
'Usage
Dim instance As New ScannerMessageEventHandler(AddressOf HandlerMethod)
```

``` csharp
public delegate void ScannerMessageEventHandler(
    IScanInfo scanInfo
)
```

``` c++
public delegate void ScannerMessageEventHandler(
    IScanInfo^ scanInfo
)
```

#### Parameters

  - scanInfo  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IScanInfo](iscaninfo-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

