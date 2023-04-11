---
title: ISalesOrderV1.ShowSalesOrders Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: ShowSalesOrders Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ISalesOrderV1.ShowSalesOrders(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.isalesorderv1.showsalesorders(v=AX.60)
ms:contentKeyID: 47344246
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ISalesOrderV1.ShowSalesOrders
dev_langs:
- CSharp
- C++
- VB
---

# ShowSalesOrders Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Displays Sales Order list.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub ShowSalesOrders ( _
    posTransaction As IPosTransaction _
)
'Usage
Dim instance As ISalesOrderV1
Dim posTransaction As IPosTransaction

instance.ShowSalesOrders(posTransaction)
```

``` csharp
void ShowSalesOrders(
    IPosTransaction posTransaction
)
```

``` c++
void ShowSalesOrders(
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

