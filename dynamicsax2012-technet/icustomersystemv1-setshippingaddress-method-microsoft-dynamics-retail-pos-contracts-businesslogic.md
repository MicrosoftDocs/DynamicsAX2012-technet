---
title: ICustomerSystemV1.SetShippingAddress Method  (Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic)
TOCTitle: SetShippingAddress Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.ICustomerSystemV1.SetShippingAddress(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IAddress)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.businesslogic.icustomersystemv1.setshippingaddress(v=AX.60)
ms:contentKeyID: 47128770
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.ICustomerSystemV1.SetShippingAddress
dev_langs:
- CSharp
- C++
- VB
---

# SetShippingAddress Method

Sets the shipping address for the transaction.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub SetShippingAddress ( _
    retailTransaction As IRetailTransaction, _
    shippingAddress As IAddress _
)
'Usage
Dim instance As ICustomerSystemV1
Dim retailTransaction As IRetailTransaction
Dim shippingAddress As IAddress

instance.SetShippingAddress(retailTransaction, _
    shippingAddress)
```

``` csharp
void SetShippingAddress(
    IRetailTransaction retailTransaction,
    IAddress shippingAddress
)
```

``` c++
void SetShippingAddress(
    IRetailTransaction^ retailTransaction, 
    IAddress^ shippingAddress
)
```

#### Parameters

  - retailTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction](iretailtransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - shippingAddress  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IAddress](iaddress-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[ICustomerSystemV1 Interface](icustomersystemv1-interface-microsoft-dynamics-retail-pos-contracts-businesslogic.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic Namespace](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)

