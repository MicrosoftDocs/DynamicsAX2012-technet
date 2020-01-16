---
title: ISalesOrder Interface (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: ISalesOrder Interface
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ISalesOrder
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.isalesorder(v=AX.60)
ms:contentKeyID: 47344015
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ISalesOrder
dev_langs:
- CSharp
- C++
- VB
---

# ISalesOrder Interface

The Microsoft.Dynamics.Retail.Pos.Contracts.Services.ISalesOrder interface for sales order.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
<GuidAttribute("9EF4FA1F-5AF1-4084-81E0-772D96B30377")> _
Public Interface ISalesOrder _
    Inherits IService, ISalesOrderV1, ISalesOrderV2, ISalesOrderV3
'Usage
Dim instance As ISalesOrder
```

``` csharp
[GuidAttribute("9EF4FA1F-5AF1-4084-81E0-772D96B30377")]
public interface ISalesOrder : IService, 
    ISalesOrderV1, ISalesOrderV2, ISalesOrderV3
```

``` c++
[GuidAttribute(L"9EF4FA1F-5AF1-4084-81E0-772D96B30377")]
public interface class ISalesOrder : IService, 
    ISalesOrderV1, ISalesOrderV2, ISalesOrderV3
```

## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

