---
title: ICashDrawer Interface (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: ICashDrawer Interface
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICashDrawer
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.icashdrawer(v=AX.60)
ms:contentKeyID: 47343854
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICashDrawer
dev_langs:
- CSharp
- C++
- VB
---

# ICashDrawer Interface

The Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICashDrawer interface is the cash drawer device interface.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
<GuidAttribute("DB9CBDAC-9325-47EE-A0E9-8A2FB45F5356")> _
Public Interface ICashDrawer _
    Inherits ICashDrawerV1, IPeripheral, IPeripheralV1, IPeripheralV2,  _
    ICashDrawerV2
'Usage
Dim instance As ICashDrawer
```

``` csharp
[GuidAttribute("DB9CBDAC-9325-47EE-A0E9-8A2FB45F5356")]
public interface ICashDrawer : ICashDrawerV1, 
    IPeripheral, IPeripheralV1, IPeripheralV2, ICashDrawerV2
```

``` c++
[GuidAttribute(L"DB9CBDAC-9325-47EE-A0E9-8A2FB45F5356")]
public interface class ICashDrawer : ICashDrawerV1, 
    IPeripheral, IPeripheralV1, IPeripheralV2, ICashDrawerV2
```

## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

