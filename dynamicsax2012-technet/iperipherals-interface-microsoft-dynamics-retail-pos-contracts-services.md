---
title: IPeripherals Interface (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: IPeripherals Interface
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPeripherals
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iperipherals(v=AX.60)
ms:contentKeyID: 47343922
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPeripherals
dev_langs:
- CSharp
- C++
- VB
---

# IPeripherals Interface

The Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPeripherals peripherals interface is a facade for various peripheral devices.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
<GuidAttribute("9F98C1B7-3FD9-4337-B958-746E94E368BD")> _
Public Interface IPeripherals _
    Inherits IService, IPeripheralsV1, IPeripheralsV2, IPeripheralsV3
'Usage
Dim instance As IPeripherals
```

``` csharp
[GuidAttribute("9F98C1B7-3FD9-4337-B958-746E94E368BD")]
public interface IPeripherals : IService, 
    IPeripheralsV1, IPeripheralsV2, IPeripheralsV3
```

``` c++
[GuidAttribute(L"9F98C1B7-3FD9-4337-B958-746E94E368BD")]
public interface class IPeripherals : IService, 
    IPeripheralsV1, IPeripheralsV2, IPeripheralsV3
```

## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

