---
title: ITax Interface (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: ITax Interface
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ITax
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.itax(v=AX.60)
ms:contentKeyID: 47344139
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ITax
dev_langs:
- CSharp
- C++
- VB
---

# ITax Interface

The Microsoft.Dynamics.Retail.Pos.Contracts.Services.ITax interface provides methods for retrieving and calculating taxes for the transaction.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
<GuidAttribute("5F21BA05-34A2-4252-AB88-54A044154EA9")> _
Public Interface ITax _
    Inherits IService, ITaxV1, ITaxV2
'Usage
Dim instance As ITax
```

``` csharp
[GuidAttribute("5F21BA05-34A2-4252-AB88-54A044154EA9")]
public interface ITax : IService, ITaxV1, 
    ITaxV2
```

``` c++
[GuidAttribute(L"5F21BA05-34A2-4252-AB88-54A044154EA9")]
public interface class ITax : IService, 
    ITaxV1, ITaxV2
```

## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

