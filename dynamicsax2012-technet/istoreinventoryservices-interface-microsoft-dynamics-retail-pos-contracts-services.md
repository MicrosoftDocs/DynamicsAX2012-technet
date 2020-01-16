---
title: IStoreInventoryServices Interface (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: IStoreInventoryServices Interface
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IStoreInventoryServices
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.istoreinventoryservices(v=AX.60)
ms:contentKeyID: 47344111
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IStoreInventoryServices
dev_langs:
- CSharp
- C++
- VB
---

# IStoreInventoryServices Interface

The Microsoft.Dynamics.Retail.Pos.Contracts.Services.IStoreInventoryServices interface for store inventory services, which manage communication with HQ for stock count and purchase order receipt features.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
<GuidAttribute("66022BF0-721E-48DD-917C-5FC7E521613F")> _
Public Interface IStoreInventoryServices _
    Inherits IService, IStoreInventoryServicesV1
'Usage
Dim instance As IStoreInventoryServices
```

``` csharp
[GuidAttribute("66022BF0-721E-48DD-917C-5FC7E521613F")]
public interface IStoreInventoryServices : IService, 
    IStoreInventoryServicesV1
```

``` c++
[GuidAttribute(L"66022BF0-721E-48DD-917C-5FC7E521613F")]
public interface class IStoreInventoryServices : IService, 
    IStoreInventoryServicesV1
```

## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

