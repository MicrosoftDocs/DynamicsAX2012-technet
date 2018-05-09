---
title: IBlankOperations Interface (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: IBlankOperations Interface
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IBlankOperations
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.iblankoperations(v=AX.60)
ms:contentKeyID: 47344241
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IBlankOperations
dev_langs:
- CSharp
- C++
- VB
---

# IBlankOperations Interface

The Microsoft.Dynamics.Retail.Pos.Contracts.Services.IBlankOperations class interface enables retail POS to be extended with new operations by third-party developers.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
<GuidAttribute("EC1010A3-1D07-4DA5-A5AD-264AE18FA46E")> _
Public Interface IBlankOperations _
    Inherits IService, IBlankOperationsV1
'Usage
Dim instance As IBlankOperations
```

``` csharp
[GuidAttribute("EC1010A3-1D07-4DA5-A5AD-264AE18FA46E")]
public interface IBlankOperations : IService, 
    IBlankOperationsV1
```

``` c++
[GuidAttribute(L"EC1010A3-1D07-4DA5-A5AD-264AE18FA46E")]
public interface class IBlankOperations : IService, 
    IBlankOperationsV1
```

## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

