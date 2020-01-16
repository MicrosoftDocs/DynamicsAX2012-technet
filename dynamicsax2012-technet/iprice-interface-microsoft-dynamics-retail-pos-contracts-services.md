---
title: IPrice Interface (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: IPrice Interface
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPrice
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iprice(v=AX.60)
ms:contentKeyID: 47344156
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPrice
dev_langs:
- CSharp
- C++
- VB
---

# IPrice Interface

The Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPrice interface gets price information from the database according to a customer's situation.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
<GuidAttribute("85DF444A-F5D6-42FD-A293-5DDC28419219")> _
Public Interface IPrice _
    Inherits IService, IPriceV1, IPriceV2
'Usage
Dim instance As IPrice
```

``` csharp
[GuidAttribute("85DF444A-F5D6-42FD-A293-5DDC28419219")]
public interface IPrice : IService, IPriceV1, 
    IPriceV2
```

``` c++
[GuidAttribute(L"85DF444A-F5D6-42FD-A293-5DDC28419219")]
public interface class IPrice : IService, 
    IPriceV1, IPriceV2
```

## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

