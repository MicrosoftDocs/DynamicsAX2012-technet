---
title: ISalesOrderV1.CustomerOrderDetails Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: CustomerOrderDetails Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ISalesOrderV1.CustomerOrderDetails(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.isalesorderv1.customerorderdetails(v=AX.60)
ms:contentKeyID: 47343882
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ISalesOrderV1.CustomerOrderDetails
dev_langs:
- CSharp
- C++
- VB
---

# CustomerOrderDetails Method

Returns the customer order details

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function CustomerOrderDetails ( _
    retailTransaction As IRetailTransaction _
) As IRetailTransaction
'Usage
Dim instance As ISalesOrderV1
Dim retailTransaction As IRetailTransaction
Dim returnValue As IRetailTransaction

returnValue = instance.CustomerOrderDetails(retailTransaction)
```

``` csharp
IRetailTransaction CustomerOrderDetails(
    IRetailTransaction retailTransaction
)
```

``` c++
IRetailTransaction^ CustomerOrderDetails(
    IRetailTransaction^ retailTransaction
)
```

#### Parameters

  - retailTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction](iretailtransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction](iretailtransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  
The customer order transaction.  

## See Also

#### Reference

[ISalesOrderV1 Interface](isalesorderv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

