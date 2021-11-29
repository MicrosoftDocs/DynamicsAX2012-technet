---
title: IPeripheralsV2.LogOnDevice Property  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: LogOnDevice Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPeripheralsV2.LogOnDevice
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iperipheralsv2.logondevice(v=AX.60)
ms:contentKeyID: 49844942
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPeripheralsV2.LogOnDevice
dev_langs:
- CSharp
- C++
- VB
---

# LogOnDevice Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

LogOn peripheral device.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property LogOnDevice As ILogOnDevice
    Get
'Usage
Dim instance As IPeripheralsV2
Dim value As ILogOnDevice

value = instance.LogOnDevice
```

``` csharp
ILogOnDevice LogOnDevice { get; }
```

``` c++
property ILogOnDevice^ LogOnDevice {
    ILogOnDevice^ get ();
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Services.ILogOnDevice](ilogondevice-interface-microsoft-dynamics-retail-pos-contracts-services.md)  
Returns [ILogOnDevice](ilogondevice-interface-microsoft-dynamics-retail-pos-contracts-services.md).  

## See Also

#### Reference

[IPeripheralsV2 Interface](iperipheralsv2-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

