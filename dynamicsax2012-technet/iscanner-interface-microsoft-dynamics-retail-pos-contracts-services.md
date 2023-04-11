---
title: IScanner Interface (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: IScanner Interface
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IScanner
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iscanner(v=AX.60)
ms:contentKeyID: 47343860
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IScanner
dev_langs:
- CSharp
- C++
- VB
---

# IScanner Interface


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Interface for scanner device.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
<GuidAttribute("7E252B1F-D5E5-4A73-9271-89F63BF195F9")> _
Public Interface IScanner _
    Inherits IScannerV1, IPeripheral, IPeripheralV1, IPeripheralV2
'Usage
Dim instance As IScanner
```

``` csharp
[GuidAttribute("7E252B1F-D5E5-4A73-9271-89F63BF195F9")]
public interface IScanner : IScannerV1, 
    IPeripheral, IPeripheralV1, IPeripheralV2
```

``` c++
[GuidAttribute(L"7E252B1F-D5E5-4A73-9271-89F63BF195F9")]
public interface class IScanner : IScannerV1, 
    IPeripheral, IPeripheralV1, IPeripheralV2
```

## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

