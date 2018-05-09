---
title: IUtilityV2.CreateCustomerOrderTransaction Method (IRetailTransaction, ISalesOrder) (Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic)
TOCTitle: CreateCustomerOrderTransaction Method (IRetailTransaction, ISalesOrder)
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.IUtilityV2.CreateCustomerOrderTransaction(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction,Microsoft.Dynamics.Retail.Pos.Contracts.Services.ISalesOrder)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.businesslogic.iutilityv2.createcustomerordertransaction(v=AX.60)
ms:contentKeyID: 49830228
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# CreateCustomerOrderTransaction Method (IRetailTransaction, ISalesOrder)

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function CreateCustomerOrderTransaction ( _
    retailTransaction As IRetailTransaction, _
    salesOrderService As ISalesOrder _
) As ICustomerOrderTransaction
'Usage
Dim instance As IUtilityV2
Dim retailTransaction As IRetailTransaction
Dim salesOrderService As ISalesOrder
Dim returnValue As ICustomerOrderTransaction

returnValue = instance.CreateCustomerOrderTransaction(retailTransaction, _
    salesOrderService)
```

``` csharp
ICustomerOrderTransaction CreateCustomerOrderTransaction(
    IRetailTransaction retailTransaction,
    ISalesOrder salesOrderService
)
```

``` c++
ICustomerOrderTransaction^ CreateCustomerOrderTransaction(
    IRetailTransaction^ retailTransaction, 
    ISalesOrder^ salesOrderService
)
```

#### Parameters

  - retailTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction](iretailtransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - salesOrderService  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Services.ISalesOrder](isalesorder-interface-microsoft-dynamics-retail-pos-contracts-services.md)  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomerOrderTransaction](icustomerordertransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[IUtilityV2 Interface](iutilityv2-interface-microsoft-dynamics-retail-pos-contracts-businesslogic.md)

[CreateCustomerOrderTransaction Overload](iutilityv2-createcustomerordertransaction-method-microsoft-dynamics-retail-pos-contracts-businesslogic.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic Namespace](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)

