---
title: ISalesOrderV1.PriceOverride Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: PriceOverride Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ISalesOrderV1.PriceOverride(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction,System.Object)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.isalesorderv1.priceoverride(v=AX.60)
ms:contentKeyID: 47344422
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ISalesOrderV1.PriceOverride
dev_langs:
- CSharp
- C++
- VB
---

# PriceOverride Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Manages the price-override operation for sales order.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub PriceOverride ( _
    posTransaction As IPosTransaction, _
    operationInfo As Object _
)
'Usage
Dim instance As ISalesOrderV1
Dim posTransaction As IPosTransaction
Dim operationInfo As Object

instance.PriceOverride(posTransaction, _
    operationInfo)
```

``` csharp
void PriceOverride(
    IPosTransaction posTransaction,
    Object operationInfo
)
```

``` c++
void PriceOverride(
    IPosTransaction^ posTransaction, 
    Object^ operationInfo
)
```

#### Parameters

  - posTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - operationInfo  
    Type: [System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  

## See Also

#### Reference

[ISalesOrderV1 Interface](isalesorderv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

