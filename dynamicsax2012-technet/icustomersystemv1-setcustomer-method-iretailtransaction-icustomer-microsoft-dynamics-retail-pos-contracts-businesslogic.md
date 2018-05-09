---
title: ICustomerSystemV1.SetCustomer Method (IRetailTransaction, ICustomer) (Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic)
TOCTitle: SetCustomer Method (IRetailTransaction, ICustomer)
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.ICustomerSystemV1.SetCustomer(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomer)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.businesslogic.icustomersystemv1.setcustomer(v=AX.60)
ms:contentKeyID: 47128969
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# SetCustomer Method (IRetailTransaction, ICustomer)

Set the customer on the transaction, and reset customer based tax groups.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub SetCustomer ( _
    retailTransaction As IRetailTransaction, _
    customer As ICustomer _
)
'Usage
Dim instance As ICustomerSystemV1
Dim retailTransaction As IRetailTransaction
Dim customer As ICustomer

instance.SetCustomer(retailTransaction, _
    customer)
```

``` csharp
void SetCustomer(
    IRetailTransaction retailTransaction,
    ICustomer customer
)
```

``` c++
void SetCustomer(
    IRetailTransaction^ retailTransaction, 
    ICustomer^ customer
)
```

#### Parameters

  - retailTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction](iretailtransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - customer  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomer](icustomer-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[ICustomerSystemV1 Interface](icustomersystemv1-interface-microsoft-dynamics-retail-pos-contracts-businesslogic.md)

[SetCustomer Overload](icustomersystemv1-setcustomer-method-microsoft-dynamics-retail-pos-contracts-businesslogic.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic Namespace](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)

