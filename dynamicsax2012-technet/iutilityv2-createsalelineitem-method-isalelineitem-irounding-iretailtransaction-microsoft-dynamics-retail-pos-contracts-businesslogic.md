---
title: IUtilityV2.CreateSaleLineItem Method (ISaleLineItem, IRounding, IRetailTransaction) (Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic)
TOCTitle: CreateSaleLineItem Method (ISaleLineItem, IRounding, IRetailTransaction)
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.IUtilityV2.CreateSaleLineItem(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItem,Microsoft.Dynamics.Retail.Pos.Contracts.Services.IRounding,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.businesslogic.iutilityv2.createsalelineitem(v=AX.60)
ms:contentKeyID: 49836756
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# CreateSaleLineItem Method (ISaleLineItem, IRounding, IRetailTransaction)

Creates the sale line item.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function CreateSaleLineItem ( _
    item As ISaleLineItem, _
    rounding As IRounding, _
    transaction As IRetailTransaction _
) As ISaleLineItem
'Usage
Dim instance As IUtilityV2
Dim item As ISaleLineItem
Dim rounding As IRounding
Dim transaction As IRetailTransaction
Dim returnValue As ISaleLineItem

returnValue = instance.CreateSaleLineItem(item, _
    rounding, transaction)
```

``` csharp
ISaleLineItem CreateSaleLineItem(
    ISaleLineItem item,
    IRounding rounding,
    IRetailTransaction transaction
)
```

``` c++
ISaleLineItem^ CreateSaleLineItem(
    ISaleLineItem^ item, 
    IRounding^ rounding, 
    IRetailTransaction^ transaction
)
```

#### Parameters

  - item  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItem](isalelineitem-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - rounding  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Services.IRounding](irounding-interface-microsoft-dynamics-retail-pos-contracts-services.md)  

<!-- end list -->

  - transaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction](iretailtransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItem](isalelineitem-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[IUtilityV2 Interface](iutilityv2-interface-microsoft-dynamics-retail-pos-contracts-businesslogic.md)

[CreateSaleLineItem Overload](iutilityv2-createsalelineitem-method-microsoft-dynamics-retail-pos-contracts-businesslogic.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic Namespace](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)

