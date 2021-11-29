---
title: IPeripheral Interface (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: IPeripheral Interface
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPeripheral
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iperipheral(v=AX.60)
ms:contentKeyID: 47343897
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPeripheral
dev_langs:
- CSharp
- C++
- VB
---

# IPeripheral Interface


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPeripheral interface represents a peripheral device and is used for managing loading and unloading the device.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
<GuidAttribute("81E2B424-97F7-4ECF-94AB-DC2E4BEFD5AB")> _
Public Interface IPeripheral _
    Inherits IPeripheralV1, IPeripheralV2
'Usage
Dim instance As IPeripheral
```

``` csharp
[GuidAttribute("81E2B424-97F7-4ECF-94AB-DC2E4BEFD5AB")]
public interface IPeripheral : IPeripheralV1, 
    IPeripheralV2
```

``` c++
[GuidAttribute(L"81E2B424-97F7-4ECF-94AB-DC2E4BEFD5AB")]
public interface class IPeripheral : IPeripheralV1, 
    IPeripheralV2
```

## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

