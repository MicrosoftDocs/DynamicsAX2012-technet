---
title: IServicesV1.StockCount Property  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: StockCount Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IServicesV1.StockCount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iservicesv1.stockcount(v=AX.60)
ms:contentKeyID: 47344476
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IServicesV1.StockCount
dev_langs:
- CSharp
- C++
- VB
---

# StockCount Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Stock count service

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property StockCount As IStockCount
    Get
'Usage
Dim instance As IServicesV1
Dim value As IStockCount

value = instance.StockCount
```

``` csharp
IStockCount StockCount { get; }
```

``` c++
property IStockCount^ StockCount {
    IStockCount^ get ();
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Services.IStockCount](istockcount-interface-microsoft-dynamics-retail-pos-contracts-services.md)  
Returns [IStockCount](istockcount-interface-microsoft-dynamics-retail-pos-contracts-services.md) .  

## See Also

#### Reference

[IServicesV1 Interface](iservicesv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

