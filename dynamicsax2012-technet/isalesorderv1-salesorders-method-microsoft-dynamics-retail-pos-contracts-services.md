---
title: ISalesOrderV1.SalesOrders Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: SalesOrders Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ISalesOrderV1.SalesOrders(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.isalesorderv1.salesorders(v=AX.60)
ms:contentKeyID: 47344209
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ISalesOrderV1.SalesOrders
dev_langs:
- CSharp
- C++
- VB
---

# SalesOrders Method

Manages sales order items

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub SalesOrders ( _
    posTransaction As IPosTransaction _
)
'Usage
Dim instance As ISalesOrderV1
Dim posTransaction As IPosTransaction

instance.SalesOrders(posTransaction)
```

``` csharp
void SalesOrders(
    IPosTransaction posTransaction
)
```

``` c++
void SalesOrders(
    IPosTransaction^ posTransaction
)
```

#### Parameters

  - posTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[ISalesOrderV1 Interface](isalesorderv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

