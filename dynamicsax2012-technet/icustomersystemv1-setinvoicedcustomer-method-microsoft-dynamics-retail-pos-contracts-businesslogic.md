---
title: ICustomerSystemV1.SetInvoicedCustomer Method  (Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic)
TOCTitle: SetInvoicedCustomer Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.ICustomerSystemV1.SetInvoicedCustomer(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomer)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.businesslogic.icustomersystemv1.setinvoicedcustomer(v=AX.60)
ms:contentKeyID: 47127991
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.ICustomerSystemV1.SetInvoicedCustomer
dev_langs:
- CSharp
- C++
- VB
---

# SetInvoicedCustomer Method

Set the transaction's Invoiced Customer.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub SetInvoicedCustomer ( _
    retailTransaction As IRetailTransaction, _
    invoicedCustomer As ICustomer _
)
'Usage
Dim instance As ICustomerSystemV1
Dim retailTransaction As IRetailTransaction
Dim invoicedCustomer As ICustomer

instance.SetInvoicedCustomer(retailTransaction, _
    invoicedCustomer)
```

``` csharp
void SetInvoicedCustomer(
    IRetailTransaction retailTransaction,
    ICustomer invoicedCustomer
)
```

``` c++
void SetInvoicedCustomer(
    IRetailTransaction^ retailTransaction, 
    ICustomer^ invoicedCustomer
)
```

#### Parameters

  - retailTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction](iretailtransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - invoicedCustomer  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomer](icustomer-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[ICustomerSystemV1 Interface](icustomersystemv1-interface-microsoft-dynamics-retail-pos-contracts-businesslogic.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic Namespace](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)

