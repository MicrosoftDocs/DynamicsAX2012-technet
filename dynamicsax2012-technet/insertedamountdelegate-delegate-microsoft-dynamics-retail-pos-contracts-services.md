---
title: InsertedAmountDelegate Delegate (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: InsertedAmountDelegate Delegate
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.Services.InsertedAmountDelegate
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.insertedamountdelegate(v=AX.60)
ms:contentKeyID: 47344210
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.InsertedAmountDelegate
dev_langs:
- CSharp
- C++
- VB
---

# InsertedAmountDelegate Delegate


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The Microsoft.Dynamics.Retail.Pos.Contracts.Services.InsertedAmountDelegate interface is the inserted amount delegate interface.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Public Delegate Sub InsertedAmountDelegate ( _
    totalAmount As Decimal, _
    status As CashGuardStaus, _
    mode As Short _
)
'Usage
Dim instance As New InsertedAmountDelegate(AddressOf HandlerMethod)
```

``` csharp
public delegate void InsertedAmountDelegate(
    decimal totalAmount,
    CashGuardStaus status,
    short mode
)
```

``` c++
public delegate void InsertedAmountDelegate(
    Decimal totalAmount, 
    CashGuardStaus status, 
    short mode
)
```

#### Parameters

  - totalAmount  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - status  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Services.CashGuardStaus](cashguardstaus-enumeration-microsoft-dynamics-retail-pos-contracts-services.md)  

<!-- end list -->

  - mode  
    Type: [System.Int16](https://technet.microsoft.com/library/e07e6fds\(v=ax.60\))  

## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

