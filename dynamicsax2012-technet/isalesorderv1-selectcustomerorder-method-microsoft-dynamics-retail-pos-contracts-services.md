---
title: ISalesOrderV1.SelectCustomerOrder Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: SelectCustomerOrder Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ISalesOrderV1.SelectCustomerOrder(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.isalesorderv1.selectcustomerorder(v=AX.60)
ms:contentKeyID: 47343906
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ISalesOrderV1.SelectCustomerOrder
dev_langs:
- CSharp
- C++
- VB
---

# SelectCustomerOrder Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Manages sales order items, triggered when the sales order operation is called.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function SelectCustomerOrder ( _
    posTransaction As IPosTransaction _
) As IPosTransaction
'Usage
Dim instance As ISalesOrderV1
Dim posTransaction As IPosTransaction
Dim returnValue As IPosTransaction

returnValue = instance.SelectCustomerOrder(posTransaction)
```

``` csharp
IPosTransaction SelectCustomerOrder(
    IPosTransaction posTransaction
)
```

``` c++
IPosTransaction^ SelectCustomerOrder(
    IPosTransaction^ posTransaction
)
```

#### Parameters

  - posTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  
The selected customer order transaction  

## See Also

#### Reference

[ISalesOrderV1 Interface](isalesorderv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

