---
title: ILogOnDeviceV1.DataReceived Event (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: DataReceived Event
ms:assetid: E:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ILogOnDeviceV1.DataReceived
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.ilogondevicev1.datareceived(v=AX.60)
ms:contentKeyID: 49818936
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ILogOnDeviceV1.DataReceived
dev_langs:
- CSharp
- C++
- VB
---

# DataReceived Event


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Log on device message event.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Event DataReceived As LogOnDeviceEventHandler
'Usage
Dim instance As ILogOnDeviceV1
Dim handler As LogOnDeviceEventHandler

AddHandler instance.DataReceived, handler
```

``` csharp
event LogOnDeviceEventHandler DataReceived
```

``` c++
 event LogOnDeviceEventHandler^ DataReceived {
    void add (LogOnDeviceEventHandler^ value);
    void remove (LogOnDeviceEventHandler^ value);
}
```

## See Also

#### Reference

[ILogOnDeviceV1 Interface](ilogondevicev1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

