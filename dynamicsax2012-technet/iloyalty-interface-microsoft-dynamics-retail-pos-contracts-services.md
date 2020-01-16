---
title: ILoyalty Interface (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: ILoyalty Interface
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ILoyalty
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iloyalty(v=AX.60)
ms:contentKeyID: 47344337
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ILoyalty
dev_langs:
- CSharp
- C++
- VB
---

# ILoyalty Interface

The Microsoft.Dynamics.Retail.Pos.Contracts.Services.ILoyalty interface provides basic loyalty functionality.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
<GuidAttribute("160D4F37-F507-4527-81CA-7ABFA80A9209")> _
Public Interface ILoyalty _
    Inherits IService, ILoyaltyV1, ILoyaltyV2, ILoyaltyV3,  _
    ILoyaltyV4
'Usage
Dim instance As ILoyalty
```

``` csharp
[GuidAttribute("160D4F37-F507-4527-81CA-7ABFA80A9209")]
public interface ILoyalty : IService, 
    ILoyaltyV1, ILoyaltyV2, ILoyaltyV3, ILoyaltyV4
```

``` c++
[GuidAttribute(L"160D4F37-F507-4527-81CA-7ABFA80A9209")]
public interface class ILoyalty : IService, 
    ILoyaltyV1, ILoyaltyV2, ILoyaltyV3, ILoyaltyV4
```

## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

