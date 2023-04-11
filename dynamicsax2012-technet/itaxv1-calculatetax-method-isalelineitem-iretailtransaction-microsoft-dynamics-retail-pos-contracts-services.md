---
title: ITaxV1.CalculateTax Method (ISaleLineItem, IRetailTransaction) (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: CalculateTax Method (ISaleLineItem, IRetailTransaction)
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ITaxV1.CalculateTax(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItem,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.itaxv1.calculatetax(v=AX.60)
ms:contentKeyID: 47344065
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# CalculateTax Method (ISaleLineItem, IRetailTransaction)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Calculates tax for a single line item

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub CalculateTax ( _
    lineItem As ISaleLineItem, _
    transaction As IRetailTransaction _
)
'Usage
Dim instance As ITaxV1
Dim lineItem As ISaleLineItem
Dim transaction As IRetailTransaction

instance.CalculateTax(lineItem, transaction)
```

``` csharp
void CalculateTax(
    ISaleLineItem lineItem,
    IRetailTransaction transaction
)
```

``` c++
void CalculateTax(
    ISaleLineItem^ lineItem, 
    IRetailTransaction^ transaction
)
```

#### Parameters

  - lineItem  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItem](isalelineitem-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - transaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction](iretailtransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[ITaxV1 Interface](itaxv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[CalculateTax Overload](itaxv1-calculatetax-method-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

