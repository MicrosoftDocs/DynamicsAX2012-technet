---
title: IDiscount Interface (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: IDiscount Interface
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IDiscount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.idiscount(v=AX.60)
ms:contentKeyID: 47344062
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IDiscount
dev_langs:
- CSharp
- C++
- VB
---

# IDiscount Interface


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The Microsoft.Dynamics.Retail.Pos.Contracts.Services. IDiscount interface calculates discounts on item and transactions.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
<GuidAttribute("EFD8BC5E-7D25-4F02-9054-F0617C32406F")> _
Public Interface IDiscount _
    Inherits IService, IDiscountV1, IDiscountV2
'Usage
Dim instance As IDiscount
```

``` csharp
[GuidAttribute("EFD8BC5E-7D25-4F02-9054-F0617C32406F")]
public interface IDiscount : IService, 
    IDiscountV1, IDiscountV2
```

``` c++
[GuidAttribute(L"EFD8BC5E-7D25-4F02-9054-F0617C32406F")]
public interface class IDiscount : IService, 
    IDiscountV1, IDiscountV2
```

## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

